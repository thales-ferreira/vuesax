<template>
  <div class="hello">
    <vs-row vs-type="flex" vs-justify="center" vs-align="center" vs-w="12">
      <vs-col vs-type="flex" vs-justify="center" vs-align="center">
        <vs-divider color="dark" border-style="dashed" icon="pets"></vs-divider>
      </vs-col>
      <vs-col vs-type="flex" vs-justify="center" vs-align="center">
        <vs-button type="filled">Hello World</vs-button>
      </vs-col>
    </vs-row>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
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
