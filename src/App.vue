<template>
  <!-- <router-view /> -->
  <button type="button" @click="count++">count is: {{ count }}</button>
</template>

<script setup lang="ts">
import { h, ref } from 'vue';

const count = ref(0);
const msg = ref('asdf');
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  user-select: none;
}
</style>
