<template>
  <div>
    <h3>Welcome {{name}}!</h3>
    <p>Gender: {{gender}}</p>
    <p>Position: {{position}}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      name: "Rajendra",
      gender: "Male",
      position: "Senior Developer",
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