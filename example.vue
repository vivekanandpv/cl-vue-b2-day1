<template>
  <div>
    <input type="text" :class="cssClass" :value="name" />
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: "Rajendra",
      cssClass: "foo",
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