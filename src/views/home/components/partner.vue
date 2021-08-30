<template>
  <div class="partner clearfix">
    <div class="big-title">Partner’s results</div>
    <div class="big-des">
      <div class="p1">All data is stored in the blockchain and can be verified by clicking on the smart contract address</div>
      <div class="p2">TRC-20 USDT smart contract address: <b>0521fffdfdkjklklllllllllll533233hhfdfdfdgghhhhhhhh</b></div>
      <div class="swiperBox">
        <ul class="list">
          <li class="yellow">
            <div class="top">
              <img src="~@/assets/icn_team.png" alt="">
              <span>88</span>
              <div class="fr">ID 33508</div>
            </div>
            <div class="con">
              <p class="t">Result in USD</p>
              <p class="whire">$ 8 788 888</p>
              <p class="t">Result in TRC-20</p>
              <p class="whire">888.888.525  USDT</p>
              <p class="t">Join Date</p>
              <p class="whire">21.08.2020</p>
            </div>
          </li>
          <li class="blue cur">
            <div class="top">
              <img src="~@/assets/icn_team.png" alt="">
              <span>88</span>
              <div class="fr">ID 33508</div>
            </div>
            <div class="con">
              <p class="t">Result in USD</p>
              <p class="whire">$ 8 788 888</p>
              <p class="t">Result in TRC-20</p>
              <p class="whire">888.888.525  USDT</p>
              <p class="t">Join Date</p>
              <p class="whire">21.08.2020</p>
            </div>
          </li>
          <li class="red">
            <div class="top">
              <img src="~@/assets/icn_team.png" alt="">
              <span>88</span>
              <div class="fr">ID 33508</div>
            </div>
            <div class="con">
              <p class="t">Result in USD</p>
              <p class="whire">$ 8 788 888</p>
              <p class="t">Result in TRC-20</p>
              <p class="whire">888.888.525  USDT</p>
              <p class="t">Join Date</p>
              <p class="whire">21.08.2020</p>
            </div>
          </li>
        </ul>
        <div class="swiper-btn prev"></div>
        <div class="swiper-btn next"></div>
      </div>
      <div class="trc">
        <div class="tit">TRC - 20 USDT</div>
        <ul class="clearfix">
          <li>
            <b>1  601  185  435 <span class="green">+978</span></b>
            <p>number of accounts</p>
          </li>
          <li>
            <b>1  898  147  777  $</b>
            <p>Total turnover, USD</p>
          </li>
        </ul>
      </div>
    </div>
    <img class="partner_icon1" src="~@/assets/partner_icon1.png" alt="">
    <img class="partner_icon2" src="~@/assets/partner_icon2.png" alt="">
  </div>
</template>

<script>
export default {
  name: 'partner',
  components: {
  },
  data() {
    return {
    };
  },
};
</script>

<style scoped lang="scss">
.partner {
  position: relative;
  text-align: center;
  background: rgba(255,255,255,0.6);
  .partner_icon1 {
    position: absolute;
    right: -80px;
    bottom: -30px;
    width: 260px;
  }
  .partner_icon2 {
    position: absolute;
    left: -40px;
    bottom: -120px;
    width: 220px;
  }
  .big-title {
    font-family: Gotham-Bold;
    font-size: 60px;
    color: $fontColor1;
    padding: 70px 0 20px 0;
  }
  .big-des {
    font-family: Gotham-Book;
    font-size: 24px;
    color: #6e3607;
    line-height: 40px;
    .p2 {
      color: $fontColor1;
    }
  }
  .swiperBox {
    width: 1280px;
    height: 330px;
    margin: 40px auto 70px auto;
    position: relative;
    .swiper-btn {
      width: 68px;
      height: 68px;
      cursor: pointer;
      position: absolute;
      &.prev {
        left: -160px;
        top: 50%;
        margin-top: -34px;
        background: url('~@/assets/ico_arrowleft.png') no-repeat center center / auto 100%;
      }
      &.next {
        right: -160px;
        top: 50%;
        margin-top: -34px;
        background: url('~@/assets/icn_arrowright.png') no-repeat center center / auto 100%;
      }
    }
    .list {
      li {
        width: 426px;
        height: 330px;
        float: left;
        margin-right: 0px;
        box-shadow: -1px 8px 15px 1px rgba(49, 49, 49, 0.27);
        border-radius: 20px;
        text-align: left;
        padding: 10px 16px 0 35px;
        background: url('~@/assets/bluebg.png') no-repeat center center / 100% 100%;
        transform: scale(0.8);
        &.yellow {
          background: url('~@/assets/yellowbg.png') no-repeat center center / 100% 100%;
        }
        &.blue {
          background: url('~@/assets/bluebg.png') no-repeat center center / 100% 100%;
        }
        &.red {
          background: url('~@/assets/redbg.png') no-repeat center center / 100% 100%;
        }
        &:nth-child(3) {
          margin-right: 0;
        }
        &.cur {
          transform: scale(1);
        }
        .top {
          font-family: Gotham-Medium;
          font-size: 25px;
          color: #fff;
          img {
            width: 65px;
            vertical-align: middle;
            margin-right: 12px;
          }
          .fr {
            line-height: 68px;
          }
        }
        .con {
          .t {
            font-family: Gotham-Medium;
            font-size: 21px;
            color: $fontColor1;
            line-height: 18px;
            margin: 18px 0 17px 0;
          }
          .whire {
            font-family: Gotham-Medium;
            font-size: 34px;
            color: #fff;
            line-height: 24px;
          }
        }
      }
    }
  }
  .trc {
    width: 1440px;
    margin: 0 auto;
    padding-bottom: 60px;
    .tit {
      font-family: Gotham-Bold;
      font-size: 40px;
      color: $fontColor2;
    }
    ul {
      padding-top: 50px;
      li {
        float: left;
        width: 50%;
        color: $fontColor2;
        padding-left: 210px;
        text-align: left;
        .green {
          color: #2bd509;
          font-size: 24px;
        }
        b {
          font-family: Gotham-Bold;
          font-size: 35px;
          vertical-align: middle;
        }
        p {
          font-family: Gotham-Bold;
          font-size: 23px;
          opacity: 0.7;
        }
      }
    }
  }
}
</style>
