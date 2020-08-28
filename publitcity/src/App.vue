<template>
  <div id="app">
    <GoogleForm form="https://docs.google.com/forms/d/e/1FAIpQLSdmkcNcPzL1m50duJiPadUPHJ6w8ZvD9J-ej-mAwMmLnECP_A/viewform?embedded=true" />
  </div>
</template>

<script>
import GoogleForm from './components/GoogleForm.vue'

export default {
  name: 'App',
  components: {
    GoogleForm
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
