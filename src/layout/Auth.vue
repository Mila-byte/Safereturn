<template>
  <main-layout>
    <LogIn />
  </main-layout>
</template>

<script>
export default {
  name: 'Auth',
  components: {
    MainLayout: () => import('./index.vue'),
    LogIn: () => import('@/components/Auth/LogIn.vue')
  }
}
</script>

<style>

</style>