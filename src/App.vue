<script setup>
import VueResizable from 'vue-resizable'

</script>

<template>
  <div class="container">
    <div class="canvas">
      <vue-resizable
      :fit-parent="true"
      >
        <div class="resizable-content"></div>
      </vue-resizable>
    </div>
  </div>
</template>

<style scoped>
.container{
  min-height: 100vh;
}

.canvas{
  aspect-ratio: 1/1.414;
    background-color: red;
    max-width: 50%;
    height: 100%;
    width: 100%;
}
.resizable-content {
  height: 100%;
  width: 100%;
  background-color: aqua;
}
</style>
