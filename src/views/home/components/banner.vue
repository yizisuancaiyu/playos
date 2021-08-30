<template>
  <div class="banner">
    <div class="register-box">
      <div class="register"></div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'banner',
};
</script>

<style scoped lang="scss">
.banner {
  height: 555px;
  background: url("~@/assets/home-banner.png") no-repeat center top;
  .register-box {
    width: 1200px;
    height: 100%;
    position: relative;
    margin: 0 auto;
  }
  .register {
    width: 286px;
    height: 100px;
    position: absolute;
    left: 150px;
    top: 280px;
    background: url("~@/assets/buttonregister.png") no-repeat center top;
    &:hover {
      cursor: pointer;
      background: url("~@/assets/buttonregister_hover.png") no-repeat center top;
    }
  }
}
</style>
