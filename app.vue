<template>
  <div>
    <nuxt-link to="/" class="btn btn-info mx-3">首頁</nuxt-link>
    <nuxt-link to="/about" class="btn btn-info mx-3">about頁</nuxt-link>
    <nuxt-link to="/admin" class="btn btn-info mx-3">admin頁</nuxt-link>
    <nuxt-link to="/admin/order" class="btn btn-info mx-3">admin頁的order頁</nuxt-link>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
    
  </div>
</template>
