<template>
  <header>
<!--    <h1>{{ title }}</h1>-->
    <h1>Random Quotes with Vue.js</h1>
  </header>
</template>

<script>
export default {
  props: ["title"],
};
</script>

<style scoped>
header {
  padding: 20px;
  display: flex;
  justify-content: center;
}
h1 {
  font-size: 36px;
  color: var(--dark);
  font-weight: 700;
  text-transform: uppercase;
  margin-bottom: 10px;
  border-bottom: 5px solid var(--primary);
  text-align: center;
}
</style>