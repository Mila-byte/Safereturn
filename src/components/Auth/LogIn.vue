<template>
  <div class="log-in">
    <SafeReturn />
    <p class="log-in_text">Log In</p>
    <form class="log-in_form">
      <AuthInput />
      <AuthInput />
      <MainButton />
      <ActionButton />
    </form>
  </div>
</template>

<script>
export default {
  name: 'LogIn',
  components: {
    SafeReturn: () => import('@/components/BasicComponents/SafeReturn.vue'),
    AuthInput: () => import('@/components/BasicComponents/AuthInput.vue'),
    MainButton: () => import('@/components/BasicComponents/MainButton.vue'),
    ActionButton: () => import('@/components/BasicComponents/ActionButton.vue')
  }
}
</script>

<style lang="scss">
.log-in {
  max-width: 426px;
  margin: 0 auto;
  display: flex;
  flex-direction: column;
  align-items: center;
  &_text {
    font-size: 20px;
    line-height: 24px;
    font-family: 'Rubik', sans-serif;
    font-weight: 500;
    color: #25252D;
  }
  &_form {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
}
</style>
