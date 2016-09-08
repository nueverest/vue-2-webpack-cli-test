<template>
  <div id="app">
    <img src="./assets/logo.png">
    <VComponent></VComponent>
    <v-component></v-component>
    <vapp></vapp>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  import VComponent from './components/v-component.vue'

  export default {
    components () {
      VComponent
    },
    data () {
      return {
        msg: 'Hello Vue 2.0!'
      }
    }
  }
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
