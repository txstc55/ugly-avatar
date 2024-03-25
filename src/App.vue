<template>
  <FaceGenerator />
  <div class="bottom-text-fixed">Press space bar to generate another one, press s to save</div>
</template>

<script>
import FaceGenerator from './views/FaceGenerator.vue'

export default {
  components: { FaceGenerator },
  name: 'App',
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
.bottom-text-fixed {
  position: fixed;
  bottom: 0;
  width: 100%;
  text-align: center;
}
</style>
