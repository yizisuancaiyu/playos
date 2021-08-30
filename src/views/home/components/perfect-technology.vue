<template>
  <div class="technology">
    <img class="technology_icon1" src="~@/assets/technology_icon1.png" alt="">
    <img class="technology_icon2" src="~@/assets/technology_icon2.png" alt="">
    <ul class="nav clearfix">
      <li>
        <div class="tit">Clan</div>
        <div class="txt">Explore the articles and tips published by experts-or share your experience.</div>
        <div class="more">Read and contribute</div>
        <div class="bg"></div>
        <img class="icon" src="~@/assets/footer-icon2.png" alt="">
      </li>
      <li>
        <div class="tit">Academy</div>
        <div class="txt">Educational video platform available to all FORSAGE participants.</div>
        <div class="more">Read and contribute</div>
        <div class="bg"></div>
        <img class="icon" src="~@/assets/footer-icon3.png" alt="">
      </li>
      <li>
        <div class="tit">Support</div>
        <div class="txt">Live Chat with experts 24/7 FORSAGE knowledge base.</div>
        <div class="more">Read and contribute</div>
        <div class="bg"></div>
        <img class="icon" src="~@/assets/footer-icon4.png" alt="">
      </li>
    </ul>
    <div class="big-title">Perfect Technology</div>
    <div class="big-des">Dencentralized marketing programs are powered by revolutionary smart contract technology. The PLOS smart contract code is <b>completely publicly available</b>. You can be confident in its safety and long-term succes.</div>
    <div class="autonomous">
      <ul class="menu">
        <li class="cur">Autonomous</li>
        <li>Immutable conditions</li>
        <li>Transparent</li>
        <li>Fully automatic</li>
        <li>Decentralized</li>
        <li>100% in the network</li>
      </ul>
      <div class="content">
        <img src="~@/assets/tem_icon.png" alt="">
        <p>No hidden expence or services fees. The contract balance is always zero,</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'technology',
};
</script>

<style scoped lang="scss">
.technology {
  width: 1360px;
  height: 1055px;
  margin: 0 auto;
  position: relative;
  .technology_icon1 {
    width: 134px;
    position: absolute;
    right: -100px;
    top: -100px;
    z-index: 2;
  }
  .technology_icon2 {
    width: 250px;
    position: absolute;
    left: -190px;
    top: -40px;
    z-index: 2;
    transform: rotate(-45deg);
  }
  .nav {
    padding-top: 50px;
    li {
      width: 410px;
      height: 188px;
      color: $fontColor1;
      padding: 20px 30px;
      background-color: #f1f1f1;
      box-shadow: -1px 11px 46px 8px
      rgba(49, 49, 49, 0.45);
      border-radius: 25px;
      margin-right: 60px;
      float: left;
      position: relative;
      overflow: hidden;
      &:nth-child(2) {
        .bg {
          background: #fba93c;
        }
      }
      &:nth-child(3) {
        margin-right: 0;
        .bg {
          background: #ffb840;
        }
      }
      .tit {
        font-family: RockoUltraFLF;
        font-size: 31px;
      }
      .txt {
        width: 240px;
        font-family: Gotham-Medium;
        font-size: 16px;
        line-height: 16px;
        color: #434343;
        padding: 14px 0 24px 0;
      }
      .more {
        font-family: Gotham-Medium;
        text-decoration: underline;
        font-size: 16px;
        cursor: pointer;
      }
      .bg {
        width: 300px;
        height: 300px;
        background: #fb9737;
        position: absolute;
        top: 40px;
        right: -140px;
        transform: rotate(-45deg);
      }
      .icon {
        width: 100px;
        position: absolute;
        right: 20px;
        bottom: 14px;
      }
    }
  }
  .big-title {
    font-family: Gotham-Bold;
    font-size: 60px;
    color: $fontColor1;
    text-align: center;
    padding: 90px 0 30px 0;
  }
  .big-des {
    width: 1030px;
    text-align: center;
    margin: 0 auto 25px auto;
    font-family: Gotham-Book;
    font-size: 22px;
    line-height: 24px;
    color: $fontColor1;
  }
  .autonomous {
    width: 1240px;
    height: 445px;
    border-radius: 40px;
    margin: 0 auto;
    padding: 37px 0;
    background: rgba(255,255,255,0.5);
    position: relative;
    .menu {
      width: 420px;
      float: left;
      text-align: right;
      li {
        padding: 0 120px 0 50px;
        height: 50px;
        line-height: 50px;
        font-family: Gotham-Book;
        font-size: 22px;
        color: $fontColor1;
        cursor: pointer;
        display: inline-block;
        &:hover, &.cur {
          box-shadow: -1px 11px 19px 2px rgba(49, 49, 49, 0.13);
          border-radius: 25px;
          background: #fff;
        }
      }
    }
    .content {
      width: 818px;
      height: 370px;
      overflow: hidden;
      margin-left: 350px;
      padding: 0 68px;
      background: #fff;
      box-shadow: -1px 11px 19px 2px rgba(49, 49, 49, 0.13);
      border-radius: 40px;
      position: absolute;
      top: 37px;
      right: 60px;
      z-index: 2;
      text-align: center;
      img {
        display: block;
        width: 160px;
        margin: 60px auto 30px auto;
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
