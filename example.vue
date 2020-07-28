<template>
  <div>
    <h2 v-show="position === 'developer'">{{name}} is a developer</h2>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: "Rajendra",
      position: "janitor",
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