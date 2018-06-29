<template>
  <section>
    <h1>{{ msg }}</h1>
    <img src="../assets/logo.png">
    <p>
      I want to create a project can display PPT base on vue, reveal, webslides etc.
    </p>
    <h3>About</h3>
    <ul>
      <li><a href="https://github.com/YunYouJun/vue-reveal" target="_blank">vue-reveal</a></li>
      <li><a href="https://github.com/YunYouJun" target="_blank">@YunYouJun</a></li>
    </ul>
  </section>
</template>

<script>
export default {
  name: 'BaseStart',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
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
</style>
