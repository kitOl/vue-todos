<script setup>
import { RouterView } from 'vue-router';
import TodoHeader from './components/TodoHeader.vue';
</script>

<template>
  <TodoHeader />
  <RouterView />
</template>

<style lang="scss">
@import url(https://fonts.googleapis.com/css?family=Rubik:300,regular,500,600,700,800,900,300italic,italic,500italic,600italic,700italic,800italic,900italic);

* {
  font-family: 'Rubik', sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.container {
  max-width: 1100px;
  margin: 0 auto;
}
</style>
