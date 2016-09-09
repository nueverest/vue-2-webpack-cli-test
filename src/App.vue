<template>
  <div>
    <img src="./assets/logo.png">
    <v-component></v-component>
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
  import { default as vcomponent } from './components/v-component.vue'

  export default {
    name: 'app',
    components: {
      'v-component': vcomponent
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
