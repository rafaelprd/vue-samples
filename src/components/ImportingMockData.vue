<template>
  <div>
    <ul>
      <li v-for="item in lista" v-bind:key="item.codigo">
        {{ item.valor }}
      </li>
    </ul>
  </div>
</template>

<script>
import MockData from '../common/MockData'

export default {
  name: 'ImportingMockData',
  data() {
    return {
      lista: MockData.itens
    }
  },
  mounted() {
    console.log(MockData)
  }
}
</script>

<style scoped>
ul {
  list-style-type: none;
}
</style>