<script setup >
const route = useRoute()
</script>

<template>
  <div>
    <h2>Page首頁</h2>
    <p>目前路由路徑-route.fullPath: {{ route.fullPath }} </p>
  </div>
</template>

<style scoped></style>
