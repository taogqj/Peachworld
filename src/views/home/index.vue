<template>
  <el-container class="h-full overflow-auto">
    <el-header class="w-full fixed z-10 !px-0"><Header /></el-header>
    <el-main class="!p-0 mt-15 main"> <router-view /></el-main>
    <el-footer><Footer /></el-footer>
  </el-container>
</template>

<script setup lang="ts">
import Header from "./components/header.vue";
import Footer from "./components/footer.vue";
</script>

<style scoped></style>
