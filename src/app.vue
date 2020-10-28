<template>
  <div class="wrap">{{ msg }}</div>
</template>

<script>
export default {
  name: "wrap",
  data() {
    return {
      msg: "vue-loader success!",
    };
  },
};
</script>

<style>
.wrap {
  background-color: aqua;
}
</style>
