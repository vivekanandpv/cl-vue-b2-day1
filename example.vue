<template>
  <div>
    <h2>{{name}}</h2>
    <input type="text" :class="cssClass" v-model="name" />
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: "Rajendra",
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