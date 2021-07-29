<template>
  <div id="app">
    <main-layout></main-layout>
  </div>
</template>

<script>
export default {
  name: 'App',
  components: {
    MainLayout: () => import('@/layout')
  }
}
</script>
<style></style>
