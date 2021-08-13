<template>
  <div class="hello">
    <h1>Hello World</h1>
    <h3>
      “ Nobody ever figures out what life is all about , and it doesn't matter.
      Explore the world. Nearly everything is really interesting if you go into
      it deeply enough. ”
    </h3>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1 {
  margin: 40px 0 20px;
}

h3 {
  margin: 30px 0 0;
  max-width: 600px;
  /* text-align: left; */
  line-height: 1.5em;
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
