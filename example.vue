<template>
  <div>
    <h2 v-if="status">Predicate is true: {{name}}</h2>
    <h2 v-else>Predicate is false: {{name}}</h2>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: "Rajendra",
      status: true,
    };
  },
};
</script>

<style>
h3 {
  color: blue;
}

p {
  color: brown;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}
</style>