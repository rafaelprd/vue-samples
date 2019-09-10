<template>
  <div>
    URL definida no arquivo .env: {{ url }}
  </div>
</template>

<script>
export default {
  name: 'EnvironmentVariables',
  data() {
    return {
      url: ''
    }
  },
  mounted() {
    this.url = process.env.VUE_APP_API_URL_1
  }
}
</script>