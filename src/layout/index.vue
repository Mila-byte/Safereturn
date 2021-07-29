<template>
  <div class="base-layout">
    <div class="main-header">
      <safe-return></safe-return>
    </div>
    <div class="main-container"></div>
  </div>
</template>

<script>
export default {
  name: 'MainLayout',
  components: {
    SafeReturn: () => import('@/components/BasicComponents/SafeReturn.vue')
  }
}
</script>

<style></style>
