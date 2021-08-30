<template>
  <div class="playos">
    <img class="theplayos" src="~@/assets/theplayos.png " alt="">
    <div class="sib-title">member Calculator</div>
    <div class="des">Estimate your potential results from THE PLOS by selecting the programs and the amount of slots. The totals are indicated for 1 cycle of all selected slots.
      * All calculations are the informational purposes only and are not an offer.
    </div>
    <!-- p1 -->
    <div class="playos-p">
      <div class="top clearfix">
        <div class="tit">THE PLAYOS P1</div>
      </div>
      <div class="p1-content clearfix">
        <ul class="numbox">
          <li class="cur">1</li>
          <li>2</li>
          <li>3</li>
          <li>4</li>
          <li>5</li>
          <li>6</li>
        </ul>
        <div class="r-con">
          <p>A basic matrix program that is the best suited for those who are self-reliant and prefer to develop on their own.</p>
          <p>Cost of all selected slots</p>
          <div class="usdt mb25">5 BUSD <span>$5</span></div>
          <p>Total result in 1 cycle from selected tools</p>
          <div class="usdt big">15 BUSD <span>$5</span></div>
        </div>
      </div>
      <img class="playos-icon1" src="~@/assets/playos-icon1.png" alt="">
    </div>
    <!-- p2 -->
    <div class="playos-p">
      <div class="top clearfix">
        <div class="tit">THE PLAYOS P2</div>
      </div>
      <div class="p1-content clearfix">
        <ul class="numbox">
          <li class="cur">1</li>
          <li>2</li>
          <li>3</li>
          <li>4</li>
          <li>5</li>
          <li>6</li>
        </ul>
        <div class="r-con">
          <p>A basic matrix program that is the best suited for those who are self-reliant and prefer to develop on their own.</p>
          <p>Cost of all selected slots</p>
          <div class="usdt mb25">5 BUSD <span>$5</span></div>
          <p>Total result in 1 cycle from selected tools</p>
          <div class="usdt big">15 BUSD <span>$5</span></div>
        </div>
      </div>
      <img class="playos-icon2" src="~@/assets/playos-icon2.png" alt="">
    </div>
    <!-- p3 -->
    <div class="playos-p">
      <div class="top clearfix">
        <div class="tit">THE PLAYOS P3</div>
        <div class="total">
          <span>Total :</span>
          <img src="~@/assets/11250.png" alt="">
        </div>
      </div>
      <div class="p3-content clearfix">
        <ul class="hr-head">
          <li>Board</li>
          <li>1</li>
          <li>2</li>
          <li>3</li>
          <li>4</li>
          <li>5</li>
          <li>6</li>
        </ul>
        <div class="table">
          <ul class="left-menu">
            <li class="cur">P1</li>
            <li>P2</li>
          </ul>
          <div class="table-con">
            <ul class="u1">
              <li>Bonus Rounds</li>
              <li>3</li>
              <li>3</li>
              <li>2</li>
              <li>3</li>
              <li>3</li>
              <li>2</li>
            </ul>
            <ul class="u2">
              <li>Total Profits</li>
              <li>300</li>
              <li>600</li>
              <li>800</li>
              <li>1,600</li>
              <li>1,600</li>
              <li>3,200</li>
            </ul>
            <ul class="u1">
              <li>Bonus Rounds</li>
              <li>3</li>
              <li>3</li>
              <li>2</li>
              <li>3</li>
              <li>3</li>
              <li>2</li>
            </ul>
            <ul class="u2">
              <li>Total Profits</li>
              <li>300</li>
              <li>600</li>
              <li>800</li>
              <li>1,600</li>
              <li>1,600</li>
              <li>3,200</li>
            </ul>
          </div>
        </div>
      </div>
      <img class="playos-icon3" src="~@/assets/playos-icon3.png" alt="">
    </div>
    <!-- p4 -->
    <div class="playos-p playos-p4">
      <div class="p1-content clearfix">
        <div class="p4-title">
          Join THE PLAYOS (USDT)
        </div>
        <div class="r-con">
          <p>the total cost of all slots in all programs</p>
          <div class="usdt mb25">18.0 BUSD <span>$5</span></div>
          <p>Total result in 1 cycle from selected slots</p>
          <div class="usdt big">89.4 BUSD <span>$5</span></div>
        </div>
      </div>
      <img class="playos-icon4" src="~@/assets/playos-icon4.png" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'playos',
};
</script>

<style scoped lang="scss">
.playos {
  .theplayos {
    display: block;
    width: 960px;
    margin: 0 auto;
    padding-top: 90px;
  }
  .sib-title {
    font-family: ComicSansMS;
    font-size: 50px;
    color: #fff;
    padding: 40px 0 60px 0;
    text-align: center;
  }
  .des {
    width: 1200px;
    text-align: center;
    font-family: ComicSansMS;
    font-size: 28px;
    color: $fontColor1;
    padding-bottom: 40px;
    margin: 0 auto;
  }
  .playos-p {
    width: 1246px;
    padding: 34px 62px;
    background: rgba(255,255,255,0.8);
    box-shadow: -1px 11px 46px 5pxrgba(49, 49, 49, 0.43);
    border-radius: 60px;
    margin: 0 auto 60px auto;
    position: relative;
    .playos-icon1 {
      width: 150px;
      position: absolute;
      left: -70px;
      top: 0;
    }
    .playos-icon2 {
      height: 210px;
      position: absolute;
      left: -100px;
      bottom: 0;
    }
    .playos-icon3 {
      height: 125px;
      position: absolute;
      top: -35px;
      right: -35px;
    }
    .playos-icon4 {
      height: 140px;
      position: absolute;
      bottom: -22px;
      right: -60px;
    }
    .top {
      padding-bottom: 25px;
      .tit {
        width: 548px;
        height: 70px;
        line-height: 70px;
        float: left;
        text-align: center;
        box-shadow: 0px 0px 13px 0px rgba(49, 49, 49, 0.43);
        border-radius: 34px;
        background: #fecb76;
        font-family: RockoUltraFLF;
        font-size: 34px;
        color: $fontColor2;
      }
      .total {
        float: left;
        margin-left: 30px;
        height: 70px;
        line-height: 70px;
        span {
          font-family: RockoUltraFLF;
          font-size: 50px;
          color: $fontColor2;
          float: left;
        }
        img {
          height: 100px;
          position: relative;
          float: left;
          margin-top: -15px;
        }
      }
    }
    .p1-content {
      .numbox {
        float: left;
        width: 360px;
        padding-left: 30px;
        li {
          float: left;
          width: 86px;
          height: 90px;
          line-height: 80px;
          cursor: pointer;
          margin: 0 20px 15px 0;
          text-align: center;
          font-family: RockoUltraFLF;
          font-size: 50px;
          background: url('~@/assets/btn_number-inactive.png') no-repeat left top;
          background-size: 100% 100%;
          &:hover, &.cur {
            background: url('~@/assets/btn_number-active.png') no-repeat left top;
            background-size: 100% 100%;
          }
        }
      }
      .r-con {
        margin-left: 430px;
        font-family: Gotham-Book;
        font-size: 22px;
        color: $fontColor1;
        line-height: 24px;
        p {
          margin-bottom: 10px;
        }
        .usdt {
          color: $fontColor2;
          font-weight: bold;
          span {
            color: $fontColor1;
            margin-left: 30px;
          }
        }
      }
    }
  }
  .p3-content {
    width: 1076px;
    height: 380px;
    background-image: linear-gradient(
    #fb832e,
    #fb832e),
    linear-gradient(
    #ef7e2e,
    #ef7e2e);
    box-shadow: 0px 5px 22px 2px
    rgba(49, 49, 49, 0.3);
    border-radius: 40px;
    .hr-head {
      width: 100%;
      height: 50px;
      line-height: 60px;
      overflow: hidden;
      text-align: center;
      padding-right: 18px;
      display: flex;
      li {
        flex: 1;
        float: left;
        font-family: Gotham-Medium;
        font-size: 28px;
        color: #fff10b;
        &:nth-child(1) {
          width: 192px;
          flex: auto;
          padding-left: 82px;
        }
      }
    }
    .table {
      background-image: linear-gradient(to right, #fb8c3d , #ffb63f);
      overflow: hidden;
      box-shadow: 0px 5px 22px 2px
    rgba(49, 49, 49, 0.3);
      margin-right: 18px;
      border-radius: 0 10px 40px 20px;
      .left-menu {
        float: left;
        width: 82px;
        background: #fff;
        li {
          height: 156px;
          line-height: 156px;
          text-align: center;
          font-family: Gotham-Medium;
          font-size: 35px;
          cursor: pointer;
          color: #575cd0;
          box-shadow: 0px 5px 7px 0px rgba(39, 39, 39, 0.5);
          &.cur, &:hover {
            color: #fff;
            background: $fontColor2;
            border-radius: 0 0 0 20px;
          }
        }
      }
      .table-con {
        margin-left: 82px;
        text-align: center;
        ul {
          overflow: hidden;
          display: flex;
          li {
            flex: 1;
            float: left;
            height: 78px;
            line-height: 78px;
            &:nth-child(1) {
              width: 110px;
              flex: auto;
            }
          }
        }
        .u1 {
          background: rgba(255,255,255,0.8);
          box-shadow: 0px 5px 7px 0px rgba(39, 39, 39, 0.3);
          li {
            color: #f00;
            font-family: Gotham-Medium;
            font-size: 30px;
            border-right: 1px solid rgba(252,135,50,0.88);
          }
        }
        .u2 {
          li {
            color: #fff;
            font-family: Gotham-Medium;
            font-size: 22px;
          }
        }
      }
    }
  }
  .playos-p.playos-p4 {
    background-image: linear-gradient(24deg,
    #fb8c3d 2%,
    #ffb63f 100%),
    linear-gradient(
    #fe9c3e,
    #fe9c3e);
    background-blend-mode: normal, normal;
    opacity: 0.8;
    .p4-title {
      width: 450px;
      height: 78px;
      float: left;
      line-height: 78px;
      text-align: center;
      color: $fontColor2;
      background: #fff;
      border-radius: 40px;
      font-family: Gotham-Bold;
      font-size: 26px;
      margin-top: 30px;
      box-shadow: 0px 5px 16px 2px
    rgba(49, 49, 49, 0.3);
    }
    .r-con {
      margin-left: 560px;
    }
  }
}
</style>
