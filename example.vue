<template>
  <div>
    <p v-for="(city, index) in cities" :key="index">{{index}}. {{city}}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      cities: ["Bengaluru", "Mumbai", "Chennai", "Delhi"],
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