<template>
  <c-flex justifyContent="center" alignItems="center" flexDirection="column">
    Beacons payment page
    <c-box backgroundColor="gray.500">
      hello
      <c-flex>
        <c-input> </c-input>
      </c-flex>
    </c-box>
  </c-flex>
</template>

<script>
export default {
  name: "Index",
  props: {
    msg: String,
  },
};
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
