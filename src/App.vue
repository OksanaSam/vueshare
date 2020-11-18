<template>
  <div id="app">
    <h3>hello</h3>
    <div>
    <AppHeader msg="Welcome to Your Vue.js App"/>
    </div>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'

export default {
  name: 'App',
  components: {
    AppHeader
  }
}
</script>

<style>

</style>

