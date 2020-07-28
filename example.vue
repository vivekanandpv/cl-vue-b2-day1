<template>
  <h3>Welcome {{name}}!!!</h3>
</template>

<script>
export default {
  data: () => {
    return {
      name: "Friends",
    };
  },
};
</script>

<style>
h3 {
  color: blue;
}
</style>