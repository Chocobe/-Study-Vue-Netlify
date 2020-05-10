<template>
  <div id="app">
    <h1>Hello Vue</h1>
    <MenuComp></MenuComp>
    <router-view></router-view>
  </div>
</template>

<script>
import MenuComp from "./components/MenuComp.vue";

export default {
  components: {
    MenuComp,
  },
};
</script>

<style>

</style>