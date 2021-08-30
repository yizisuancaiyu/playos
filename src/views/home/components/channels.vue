<template>
  <div class="channels">
    <div class="title">Official channels</div>
    <ul>
      <li>
        <img src="~@/assets/icn_telegram.png" alt="">
        <p>Telegram channel</p>
      </li>
      <li>
        <img src="~@/assets/icn_telegram.png" alt="">
        <p>Telegram chat</p>
      </li>
      <li>
        <img src="~@/assets/icn_twitter.png" alt="">
        <p>Twitter</p>
      </li>
      <li>
        <img src="~@/assets/icn_Instagram.png" alt="">
        <p>Instagram</p>
      </li>
      <li>
        <img src="~@/assets/icn_fb.png" alt="">
        <p>Facebook</p>
      </li>
      <li>
        <img src="~@/assets/icn_youtube.png" alt="">
        <p>Youtube</p>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'channels',
};
</script>

<style scoped lang="scss">
.channels {
  background: rgba(255,255,255,0.4);
  text-align: center;
  .title {
    color: $fontColor1;
    font-family: Gotham-Bold;
    font-size: 60px;
    padding: 50px 0 40px 0;
  }
  ul {
    padding-bottom: 50px;
    li {
      width: 108px;
      display: inline-block;
      margin: 0 40px;
      vertical-align: top;
      img {
        width: 100%;
        display: block;
        margin-bottom: 20px;
      }
      p {
        font-family: Gotham-Book;
        font-size: 22px;
        color: $fontColor1;
      }
    }
  }
}
</style>
