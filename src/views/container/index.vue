<script setup lang="ts">
import Chat from '../chat/index.vue';
</script>

<template>
  <div class="container">
    <div class="nav">
      nav
    </div>
    <div class="content">
      <Chat />
    </div>
  </div>
</template>

<style scoped>
.container {
  display: flex;
}

.nav {
  width: 120px;
  background-color: bisque;
  height: 100%;
}

.content {
  flex: 1;
}
</style>
