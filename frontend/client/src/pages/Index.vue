<template>
  <q-page class="q-pa-xl">
    <div class="row">
      <q-input v-model="form.api_key" label="Xero Key" />
    </div>

    <div>{{ form.api_key }}</div>

    <div class="row q-mt-lg">
      <q-input v-model="form.api_secret" label="Xero Secret" />
    </div>
  </q-page>
</template>

<script>
export default {
  name: 'PageIndex',

  data() {
    return {
      form: {
        api_key: '',
        api_secret: '',
      }
    }
  }
}
</script>