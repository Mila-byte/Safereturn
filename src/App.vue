<template>
  <div class="app">
    <Auth />
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    Auth: () => import('@/layout/Auth.vue')
  }
}
</script>
<style>
</style>
