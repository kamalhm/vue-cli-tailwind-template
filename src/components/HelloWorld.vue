<template>
  <div class="bg-teal-500">
    <p class="text-6xl">{{msg}}</p>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<style>
</style>
