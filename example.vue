<template>
  <div>
    <h2>{{name}}</h2>
    <input type="text" @input="inputHandler" :value="name" />
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: "Rajendra",
    };
  },
  methods: {
    inputHandler: function (e) {
      this.name = e.target.value;
    },
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