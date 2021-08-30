<template>
  <div class="nav">
    <div class="logo">LOGO</div>
    <div class="menu">
      <ul class="list fl">
        <li>Clan</li>
        <li>Academy</li>
        <li>Support</li>
      </ul>
      <ul class="login fr">
        <li>Register</li>
        <li>Log in</li>
        <li class="user">
          <img src="~@/assets/user-icon.png" alt="">
        </li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  name: 'nav',
};
</script>

<style scoped lang="scss">
.nav {
  width: 100%;
  height: 54px;
  position: fixed;
  left: 0;
  top: 0;
  z-index: 99;
  overflow: hidden;
  background-image: linear-gradient(266deg,
    #ffb940 0%,
    #feb03b 20%,
    #fda836 39%,
    #fda434 47%,
    #fa8f28 100%),
  linear-gradient(
    #fe9c3e,
    #fe9c3e);
  background-blend-mode: normal, normal;
  .logo {
    position: absolute;
    left: 2%;
    height: 54px;
    line-height: 54px;
    color: #fff;
    font-family: AdobeHeitiStd-Regular;
    font-size: 23px;
  }
  .menu {
    width: 1200px;
    margin: 0 auto;
    li {
      float: left;
      cursor: pointer;
      line-height: 54px;
      font-family: Gotham-Medium;
      font-size: 18px;
      &:hover {
        text-decoration: underline;
      }
    }
    .list {
      li {
        margin-right: 55px;
      }
    }
    .login {
      li {
        color: $fontColor1;
        margin-left: 75px;
        &.user {
          margin-left: 140px;
          img {
            width: 36px;
            height: 36px;
            border-radius: 50%;
            margin-top: 9px;
          }
        }
      }
    }
  }
}
</style>
