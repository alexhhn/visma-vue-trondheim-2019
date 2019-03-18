<template>
  <div class="container">
    <h3>{{title}}</h3>
    <div class="field">
      <p>McDonalds (1990-2010)</p>
      <p>Servicearbeider</p>
      <p>Årets ansatt 7 år på rad</p>
    </div>
  </div>
</template>

<script>
export default {
  props: {
    title: String
  }
};
</script>

<style scoped>
.container {
  margin: 0 50px;
}

p {
  text-align: start;
}

h3 {
  text-align: start;
}
.field {
  background-color: white;
  padding: 10px;
  border-radius: 8px;
}
</style>
