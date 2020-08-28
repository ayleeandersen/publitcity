<template>
  <div class="hello">
    <h1>Welcome!</h1>
    <h2>To learn more about LDSSA, visit: <a href="https://instituteinlogan.org/ldssa/">https://instituteinlogan.org/ldssa/</a></h2>
    <h2>Sign up for the class here: <a href="https://myinstitute.churchofjesuschrist.org/classes/16878745">https://myinstitute.churchofjesuschrist.org/classes/16878745</a></h2>
    <iframe :src="form" width="640" height="1288" frameborder="0" marginheight="0" marginwidth="0" scrolling="no">Loading…</iframe>
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
