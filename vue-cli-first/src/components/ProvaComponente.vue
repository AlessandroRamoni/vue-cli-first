<template>
  <div class="hello">
    <h1>La mia prima app con Vue CLI</h1>
    <p>Un po' di testo...</p>
    <ul>
      <li>Ciao</li>
      <li>Hello</li>
      <li>Hi</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "ProvaComponente",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  margin: 40px 0 0;
  color: #42b983;
}
ul {
  margin: 0;
  padding: 0;
  list-style: none;
}
</style>
