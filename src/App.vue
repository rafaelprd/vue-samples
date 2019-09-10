<template>
  <div id="app">
    <div class="example-content">
      <environment-variables></Environment-variables>
    </div>
  </div>
</template>

<script>
import EnvironmentVariables from './components/EnvironmentVariables'

export default {
  name: 'app',
  components: {
    EnvironmentVariables
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.example-content {
  border: 1px solid rgba(100,100,100,.3);
  padding: 10px;
  margin: 20px;
}
</style>
