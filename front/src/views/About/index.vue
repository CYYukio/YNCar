<template>
  <!-- 关于一诺 -->
  <div class="About">
    <y-header></y-header>

    <y-zixun></y-zixun>
    <!-- title of about INNO-->
    <div class="banner">
      <div class="title left">
        <img src="../../assets/img_about/title.png" id="picL" />
      </div>
      <div class="title right">
        <img src="../../assets/img_about/title.png" id="picR" />
      </div>
      <div class="content">
        <img src="../../assets/img_about/banner.jpg" class="content-img" />
      </div>
      <div class="foot">
        <img src="../../assets/img_about/bg.png" class="footer-img" />
      </div>
    </div>
    <hr class="line" />
    <div class="tips-block">
      <div class="tips tL">
        <span class="word">关于我们</span>
      </div>
      <div class="tips">
        <span class="word">加入我们</span>
      </div>
      <div class="tips tR">
        <span class="word">联系我们</span>
      </div>
    </div>

    <!-- banner -->
    <div>
      <div class="img1">
        <p class="img1_title">
          一诺检测成立于
          <span class="blueWord">2016</span>年，主要为个人用户和企业用户提供
          <span class="blueWord">专业、公正、客观</span>的第三方检测服务。
        </p>
      </div>
    </div>

    <!-- 取消浮动 -->
    <div class="quxiao"></div>

    <div class="main_info">
      <div class="info_char">
        <p
          style="font-size: 20px; font-weight: bold; line-height: 40px;"
        >秉承“致力车辆买卖信息对称，健全车辆流通信用体制”的使命</p>
        <p style="color: #b6b6b6;">一诺检测建立起一支由汽车研发工程师、整车评审工程师以及资深维修技师组成的专业检测师团队</p>
        <p style="color: #b6b6b6;">只为让更多的客户可以享受到车辆买卖信息对称带来的优质体验</p>
      </div>

      <div class="main_pic">
        <div class="inner_pic">
          <div class="img2">
            <img src="@/assets/img_about/img2.jpg" class="zoom" />
          </div>
          <div class="intro1">
            <img src="@/assets/img_about/intro1.png" />
          </div>
          <div class="img3">
            <img src="@/assets/img_about/img3.jpg" class="zoom" />
          </div>
          <div class="intro2">
            <img src="@/assets/img_about/intro2.png" />
          </div>
          <div class="img4">
            <img src="@/assets/img_about/img4.jpg" class="zoom" />
          </div>
          <div class="intro3">
            <img src="@/assets/img_about/intro3.png" />
          </div>
          <div class="bg">
            <img src="@/assets/img_about/bg.jpg" />
          </div>
          <p class="bg_title">坚持“专注细节、品质服务”的理念</p>
          <hr class="line_2" />
          <div class="bg_word">
            <p class="w1">一诺检测是隶属于伤害振森汽车服务有限公司的一家第三方车辆检测平台，</p>
            <p class="w2">并以《二手车鉴定评估技术规范》的国家标准为基础，</p>
            <p class="w3">综合车辆流通市场实际需求，</p>
            <p class="w4">研发并制定出涵盖检测项目：229项的专业检测车辆鉴定评估体系，</p>
            <p class="w5">力求每一个检测细节都做到极致。</p>
          </div>
        </div>
      </div>
    </div>

    <div class="yuanquan">
      <div class="icon_3">
          <div class="iconL"></div>
          <div class="iconM"></div>
          <div class="iconR"></div>
      </div>
      
    </div>

    <div class="icon_word">
      <span class="iwl">上门检测</span>
      <span class="iwm">到店检测</span>
      <span class="iwr">陪同看车</span>
    </div>

    <div style="height: 200px; overflow: hidden;">
      <p style="font-size: 20px; font-weight: bold; line-height: 40px;">坚信“用户满意度是企业生存的基石”</p>
      <p style="color: #b6b6b6;">一诺检测率先将移动互联网技术运用到第三方检测中，用户可以通过微信、html5、电话、网站轻松享用检测服务。</p>
      <p style="color: #b6b6b6;">同时为满足用户多元化需求，一诺检测还推出了上门检测、到店检测、陪同看车等多项服务，并且支持微信、支付宝等多种的便捷支付方式。</p>
      <hr class="line_3" />
      <hr class="line_4" />
      <hr class="line_5" />
    </div>
    <div>
      <p style="position: relative; top: 60px; color: #b6b6b6;">
        不放过每一个细节，将车辆检测做到
        <span class="blueWord">极致</span>，是每一个一诺人永恒的
        <span class="blueWord">追求！</span>
      </p>
    </div>
    <div class="white">
      <div class="car">
        <div class="car1">
          <img src="@/assets/img_about/car.png" />
        </div>
        <div class="car2">
          <img src="@/assets/img_about/car.png"/>
        </div>
        <div class="car3">
          <img src="@/assets/img_about/car.png"/>
        </div>
        
      </div>

      
      <span class="carWord">值得信赖的二手车专家</span>

      <div style="width:100%;margin-top:-200px;position:relative;float:left;overflow: hidden;">
        <img src="@/assets/img_about/white.png" style="background-color:black;opacity:1;width:1500px;height:170px;">
      </div>
    </div>
    <y-footer></y-footer>
  </div>
</template>

<script>
import YHeader from "../../components/Header";
import YFooter from "../../components/Footer";
import YZixun from "../../components/zixun";
export default {
  name: "About",
  components: {
    //这里是用到等各种组件
    YHeader,
    YFooter,
    YZixun
  },
  data() {
    return {
      //这里返回变量
    };
  },
  methods: {
    moveL() {
      this.$("#picL").animate({ left: 0 }, 500);
    },
    moveR() {
      this.$("#picR").animate({ right: "100%" }, 500);
    }
  },
  mounted() {
    //这里是页面加载完毕以后要自动执行的函数
    this.moveL();
    this.moveR();
  }
};
</script>

<style scoped lang="scss">
.About {
  width: 100%;

  .quxiao{
  clear: both;
  width: 0%;
  height: 0%;
  }

  .banner {
    width: 100%;
    .content {
      height: 330px;
      overflow: hidden;
      width: 100%;
      .content-img {
        position: relative;
        left: -280px;
        height: 100%;
      }
    }
    .foot {
      overflow: hidden;
      height: 130px;
      .footer-img {
        width: 100%;
        height: 100%;
      }
    }
    .title {
      position: absolute;
      width: 90px;
      height: 316px;
      display: inline-block;
      z-index: 10;
    }
    .left {
      right: 50%;
      overflow: hidden;
      img {
        position: relative;
        left: 100%;
      }
    }
    .right {
      left: 50%;
      overflow: hidden;
      img {
        position: relative;
        right: 200%;
      }
    }
  }
  .line {
    position: relative;
    top: 10px;
    border: solid 0.3px #dddddd;
    width: 90%;
    height: 1px;
    background-color: #ffffff;
  }
  .tips-block {
    // text-align: center;
    position: relative;
    top: -18px;
    margin: 0 auto;
    background-color: #fff;
    // background-color: antiquewhite;
    width: 460px;
    height: 40px;
    .tips {
      margin: auto 0;
      width: 75px;
      height: 36px;
      color: #888888;
      font-size: 14px;
      font-weight: bold;
      display: inline-block;
      .word {
        position: relative;
        top: 8px;
      }
    }
    .tL {
      position: relative;
      right: 70px;
    }
    .tR {
      position: relative;
      left: 70px;
    }
  }

  .zoom {
    transition: all 1s;
  }
  .zoom:hover {
    transform: scale(1.3);
  }

  .img1 {
    background-image: url("~@/assets/img_about/img1.jpg");
    background-position: center;
    background-repeat: no-repeat;
    height: 235px;
    width: 100%;
    z-index: -1;
    overflow: hidden;
  }

  .img1_title {
    position: relative;
    top: 77px;
  }

  .info {
    position: relative;
    width: 100%;
    overflow: hidden;
  }
  .blueWord {
    font-size: 30px;
    color: #126db0;
  }

  .main_info {
    //position: relative;
    //margin: 0, auto;
    // left: 2;
    height: 1030px;
    width: 100%;
    overflow: hidden;
  }

  .main_pic {
    width: 100%;
  }

  .inner_pic {
    position: relative;
    left: -220px;
  }

  .img2 {
    height: 300px;
    width: 300px;
    position: relative;
    left: 355px;
    overflow: hidden;
  }

  .intro1 {
    height: 300px;
    width: 312px;
    position: relative;
    top: -300px;
    left: 643px;
  }

  .img3 {
    height: 300px;
    width: 300px;
    position: relative;
    top: -600px;
    left: 955px;
    overflow: hidden;
  }

  .intro2 {
    height: 300px;
    width: 312px;
    position: relative;
    top: -900px;
    left: 1243px;
  }

  .intro3 {
    height: 300px;
    width: 312px;
    position: relative;
    top: -1200px;
    left: 355px;
    z-index:5;
  }

  .img4 {
    height: 300px;
    width: 300px;
    position: relative;
    top: -900px;
    left: 655px;
    overflow: hidden;
    z-index:4;
  }
  .bg {
    height: 300px;
    width: 300px;
    position: relative;
    top: -1500px;
    left: 955px;
    z-index: -2;
  }
  .bg_title {
    position: relative;
    color: white;
    font-weight: bold;
    top: -1790px;
    left: 420px;
  }
  .line_2 {
    position: relative;
    top: -1785px;
    left: 324px;
    border: solid 0.3px #dddddd;
    width: 47px;
    height: 0.1px;
    background-color: #ffffff;
  }
  .bg_word {
    width: 500px;
    height: 300px;
    position: relative;
    top: -1780px;
    left: 700px;
    z-index: -1;
    .w1 {
      position: relative;
      font-weight: 20;
      left: 345px;
      color: white;
      font-size: 13px;
    }
    .w2 {
      position: relative;
      font-weight: 20;
      left: 285px;
      color: white;
      font-size: 13px;
    }
    .w3 {
      position: relative;
      font-weight: 20;
      left: 214px;
      color: white;
      font-size: 13px;
    }
    .w4 {
      position: relative;
      font-weight: 20;
      left: 322px;
      color: white;
      font-size: 13px;
    }
    .w5 {
      position: relative;
      font-weight: 20;
      left: 227px;
      color: white;
      font-size: 13px;
    }
  }

  .icon_3{
    margin-left: 330px;
    height: 80px;
    width: 100%;
  }

  .iconL {
    position: relative;
    float: left;
    background-image: url("~@/assets/img_about/icon.png");
    background-position: left;
    background-repeat: no-repeat;
    width: 77px;
    height: 80px;
    margin-right: 100px;
    margin-left: 100px;
  }

  .iconM {
    position: relative;
    float: left;
    background-image: url("~@/assets/img_about/icon.png");
    background-position: center;
    background-repeat: no-repeat;
    width: 77px;
    height: 80px;
    margin-right: 100px;
    margin-left: 100px;
  }

  .iconR {
    position: relative;
    float: left;
    background-image: url("~@/assets/img_about/icon.png");
    background-position: right;
    background-repeat: no-repeat;
    width: 77px;
    height: 80px;
    margin-right: 100px;
    margin-left: 100px;
  }

  .icon_word {
    position: relative;
    color: #d6d6d6;
    top: 10px;
    height: 50px;
    width: 1900px;
    .iwl {
      position: relative;
      left: -415px;
    }
    .iwm {
      position: relative;
      left: -205px;
    }
    .iwr {
      position: relative;
      left: 10px;
    }
  }

  .line_3 {
    position: relative;
    top: 0px;
    left: 0px;
    width: 1080px;
    height: 0.1px;
    background-color: #7f7f7f;
  }

  .line_4 {
    position: relative;
    top: -150px;
    left: 540px;
    width: 0.01px;
    height: 140px;
    background-color: #7f7f7f;
  }

  .line_5 {
    position: relative;
    top: -300px;
    right: 540px;
    width: 0.01px;
    height: 140px;
    background-color: #7f7f7f;
  }

  .white {
    background-image: url("~@/assets/img_about/white.png");
    background-position: center;
    background-repeat: no-repeat;
    width: 100%;
    height: 250px;
    //overflow: hidden;
    z-index: 5;

    .car{
      width: 100%;
      height: 238px;
      overflow: hidden;
      position: relative;
      float: left;
    }
    .car1 {
      position: relative;
      float: left;
      width: 789px;
      height: 238px;
      transition: all 2s;
      left: -2100px;
      z-index: 3;
    }

    .car2{
      position: relative;
      float: left;
      width: 789px;
      height: 238px;
      transition: all 2s;
      left: -500px;
      margin-top: -238px;
      z-index: 3;
    }

    .car3{
      position: relative;
      float: left;
      width: 789px;
      height: 238px;
      transition: all 2s;
      left: 1200px;
      margin-top: -238px;
      z-index: 3;
    }
    .car:hover .car1{
      transform: translate(1800px, 0px);
    }

    .car:hover .car2{
      transform: translate(1800px, 0px);
    }
    .car:hover .car3{
      transform: translate(1800px, 0px);
    }
  }

  
  .carWord {
    height: 10px;
    width: 50px;
    position: relative;
    top: -75px;
    font-size: 30px;
    color:white;
    z-index: 3;
    font-family: "宋体";
  }
}
</style>
