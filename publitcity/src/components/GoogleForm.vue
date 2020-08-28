<template>
  <div class="hello">
    <iframe :src="form" width="640" height="1288" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
  </div>
</template>

<script>
export default {
  name: 'GoogleForm',
  props: {
    form: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
