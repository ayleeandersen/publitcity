<template>
  <div class="hello">
    <h1>Welcome!</h1>
    <h2>Register to join Publicity <a href="https://myinstitute.churchofjesuschrist.org/classes/16878745">here</a></h2>
    <h2>To learn more about LDSSA, visit <a href="https://instituteinlogan.org/ldssa/">instituteinlogan.org/ldssa</a></h2>
    <iframe :src="form" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
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
  color: rgb(3, 169, 244);
}
iframe {
  width: 100%;
  max-width: 640px;
  height: 1500px;
}
</style>
