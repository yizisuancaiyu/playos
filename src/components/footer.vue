<template>
  <div class="footer">
    <div class="platform">
      <div class="logo">LOGO</div>
      <div class="des">The world’s first 100% decentralized matrix platform</div>
      <div class="list">
        <span class="usdt">P1 / P2 TRC - 20 USDT</span>
        <span class="phone">0441...561661</span>
        <ul>
          <li>
            <img src="~@/assets/footer-icon2.png" alt="">
            <span>TRC - 20 USDT</span>
          </li>
          <li>
            <img src="~@/assets/footer-icon2.png" alt="">
            <span>The Playos<br/>Clan</span>
          </li>
          <li>
            <img src="~@/assets/footer-icon3.png" alt="">
            <span>The Playos<br/>Acadmy</span>
          </li>
          <li>
            <img src="~@/assets/footer-icon4.png" alt="">
            <span>The Playos<br/>Support</span>
          </li>
        </ul>
      </div>
    </div>
    <div class="rights">
      <div class="text">2021 All Rights Reserved Disclaimer</div>
      <div class="chat">Chat</div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'footer',
};
</script>

<style scoped lang="scss">
.footer {
  .platform {
    text-align: center;
    background: rgba(0,0,0,0.3);
    .logo {
      font-family: Gotham-Medium;
      font-size: 36px;
      color: $fontColor3;
      padding: 18px 0 12px 0;
    }
    .des {
      font-family: Gotham-Book;
      font-size: 18px;
      opacity: 0.6;
      padding-bottom: 27px;
    }
    .list {
      padding-bottom: 26px;
      .usdt {
        opacity: 0.6;
        margin-right: 17px;
      }
      ul {
        display: inline-block;
        li {
          display: inline-block;
          margin-left: 120px;
          vertical-align: middle;
          position: relative;
          span {
            display: inline-block;
            text-align: left;
            font-family: Gotham-Book;
            font-size: 14px;
          }
          img {
            width: 34px;
            position: absolute;
            left: -40px;
            top: 50%;
            margin-top: -17px;
          }
        }
      }
    }
  }
  .rights {
    position: relative;
    background: rgba(0,0,0,0.6);
    .text {
      height: 80px;
      line-height: 80px;
      text-align: center;
      color: $fontColor3;
      font-family: Gotham-Book;
      font-size: 18px;
      opacity: 0.6;
    }
    .chat {
      width: 103px;
      height: 35px;
      line-height: 35px;
      cursor: pointer;
      font-family: RockoUltraFLF;
      font-size: 18px;
      color: #fff7f7;
      position: absolute;
      right: 20%;
      top: 22px;
      padding-left: 50px;
      background: url('~@/assets/btn_chat.png') no-repeat left top;
    }
  }
}
</style>
