<script setup lang="ts">
import AppRightView from "./components/AppRightView";
import HelloWorld from "./components/HelloWorld";
</script>

<template>
  <div>
    <span>Call by App.vue</span>
    <HelloWorld msg="You did it!" />
    <br>
    <span>Call by AppRightView.tsx</span>
    <AppRightView />
  </div>
</template>

<style scoped>
</style>
