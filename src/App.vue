<template>
  <div id="app">
    <h1>Cộng đồng công nghệ thông tin trên zalo</h1>
    <Group/>
  </div>
</template>

<script>
import Group from './components/group.vue'

export default {
  name: 'App',
  components: {
    Group
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
