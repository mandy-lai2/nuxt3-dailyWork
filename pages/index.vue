<script setup>
const route = useRoute()
</script>

<template>
  <div>
    <h2>Page首頁</h2>
    <h1>全域共用 SCSS 或 SASS 變數</h1>
    <p>目前路由路徑-route.fullPath: {{ route.fullPath }} </p>
    <p>
      <button type="button" class="btn btn-primary">Primary</button>
      <button type="button" class="btn btn-secondary">Secondary</button>
      <button type="button" class="btn btn-success">Success</button>
      <button type="button" class="btn btn-danger">Danger</button>
      <button type="button" class="btn btn-warning">Warning</button>
      <button type="button" class="btn btn-info">Info</button>
      <button type="button" class="btn btn-light">Light</button>
      <button type="button" class="btn btn-dark">Dark</button>

      <button type="button" class="btn btn-link">Link</button>
    </p>
  </div>
</template>

<style lang="scss">
h1 {
  color: $main-color;
}
</style>
