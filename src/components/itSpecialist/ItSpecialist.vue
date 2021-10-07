<template>
  <section class="it_specialist">
    <div class="container-absolute-it-specialist">
      <div class="number-specialist">
        20 специалистов
      </div>
      <div class="square">
        <img class="img-1" src="../../assets/img/2block/1.png" alt="1">
      </div>
      <img src="../../assets/img/2block/2.png" alt="" class="img-2">
      <img src="../../assets/img/2block/3.png" alt="" class="img-3">
      <img src="../../assets/img/2block/4.png" alt="" class="img-4">
      <img src="../../assets/img/2block/5.png" alt="" class="img-5">
      <img src="../../assets/img/2block/6.png" alt="" class="img-6">
      <img src="../../assets/img/2block/7.png" alt="" class="img-7">
      <img src="../../assets/img/2block/8.png" alt="" class="img-8">
      <img src="../../assets/img/2block/9.png" alt="" class="img-9">
      <img src="../../assets/img/2block/8.png" alt="" class="img-10">
      <img src="../../assets/img/2block/8.png" alt="" class="img-11">
      <img src="../../assets/img/2block/8.png" alt="" class="img-12">
      <img src="../../assets/img/2block/8.png" alt="" class="img-13">
      <img src="../../assets/img/2block/8.png" alt="" class="img-14">
    </div>
    <div class="container">
      <div class="wrapper">
        <h2>Своя база
          <div class="h2--green">
            &nbsp;IT-специалистов
          </div>
        </h2>
      </div>
      <div class="row">
        <div class="col-410">
          <div class="wrapper-410">
            <div class="heading">
              Наша первоочередная цель –
            </div>
            <div class="paragraph">
              обеспечить цифровое лидерство вашего бренда благодаря высокой квалификации наших разработчиков, передовым
              техлогиями и прозрачным процессом.
            </div>
          </div>
        </div>
        <div class="col-670">
          <div class="background-img-green">
            <div class="heading">
              Упор на качественный продукт
            </div>
          </div>
          <div class="paragraph">Оперативно подключим к вашему проекту команду IT-специалистов.</div>
          <div class="paragraph">Гибкие ставки. Все кандидаты уровня Middle, Senior.<br>
            Быстрый выход на проекты.Гибкие ставки. Все кандидаты уровня
            Middle, Senior. Быстрый выход на проекты.Гибкие ставки. В<br>
            се кандидаты уровня Middle, Senior. Быстрый выход на проекты.Гибк<br>
            ие ставки. Все кандидаты уровня Middle, Senior. Быстрый выход на
            проекты.
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
import ScrollReveal from 'scrollreveal';
import {CONFIG_IMG_SHOW} from "../../../constants/config";

export default {
  name: "ItSpecialist",
  methods: {
    getScroll: function () {
      for (let i = 1; i < 15; i++) {
        ScrollReveal().reveal('.img-' + i, CONFIG_IMG_SHOW)
      }
    }
  },
  mounted() {
    this.getScroll()
  }
}
</script>

<style scoped>
@keyframes moving {
  from {
    transform: rotate(0)
  }
  to {
    transform: rotate(-360deg)
  }
}

.square img {
  animation: 20s moving infinite linear;
}

.container-absolute-it-specialist, .img-2, .img-3, .img-4, .img-5, .img-6, .img-7, .img-8, .img-9, .img-10, .img-11, .img-12, .img-13, .img-14 {
  position: absolute;
}

.img-2, .img-3, .img-4, .img-5, .img-6, .img-7, .img-8, .img-9, .img-10, .img-11, .img-12, .img-13, .img-14 {
  z-index: 1;
}

.img-2 {
  left: 192px;
  top: 42px;
}

.img-3 {
  left: 288px;
  top: 23px;
}

.img-4 {
  left: 319px;
  top: 150px;
}

.img-5 {
  top: 368px;
  left: 58px;
}

.img-6 {
  top: 465px;
  left: 152px;
}

.img-7 {
  top: 734px;
  left: 45px;
}

.img-8 {
  top: 710px;
  left: 479px;
}

.img-9 {
  top: -22px;
  left: 709px;
  z-index: 0;
}

.img-10 {
  top: 762px;
  left: 568px;
}

.img-11 {
  top: 816px;
  left: 661px;
}

.img-12 {
  top: 866px;
  left: 758px;
}

.img-13 {
  top: 920px;
  left: 851px;
}

.img-14 {
  top: 978px;
  left: 948px;
}

.it_specialist {
  background-color: #f4f7f7;
  display: grid;
  z-index: -1;
}

.square {
  position: absolute;
  left: 233px;
  top: 38px;
}

.wrapper {
  display: flex;
  justify-content: flex-end;
}

.wrapper-410 {
  text-align: left;
  padding: 96px 60px;
}

.wrapper-410 .heading {
  padding-bottom: 30px;
}

.col-410 {
  max-width: 410px;
  width: 100%;
  margin-right: 50px;
  margin-left: 30px;
  background-color: #e1fccf;
  border-radius: 12px;
}

.row {
  display: flex;
  justify-content: flex-end;
  margin-top: 30px;
}

.paragraph {
  font-size: 20px;
  color: #0f0000;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: 300;
}

.paragraph + .paragraph {
  margin-top: 25px;
  max-width: 610px;
}

.wrapper-410 .heading {
  font-size: 30px;
  color: #000000;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: 500;
}

.col-670 .paragraph {
  margin-left: 35px;
  text-align: left;
  max-width: 670px;
  width: 100%;
}

.background-img-green .heading {
  padding: 55px;
  font-size: 30px;
  line-height: 47px;
  color: #000000;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: 500;
}

.background-img-green {
  background-image: url("../../assets/img/background-green.png");
  margin-top: 20px;
  margin-bottom: 90px;
  -moz-background-size: 100%;
  -webkit-background-size: 100%;
  -o-background-size: 100%;
  background-size: 100%;
}

.number-specialist {
  width: 200px;
  position: absolute;
  top: 130px;
  left: 70px;
  -webkit-transform: rotate(
      -90deg);
  -moz-transform: rotate(-90deg);
  transform: rotate(
      -90deg);
  font-size: 21px;
  line-height: 37px;
  color: #000000;
  font-family: "GT Eesti Pro Display", serif;
}

.container {
  padding: 0 290px;
}

.container h2 {
  font-size: 50px;
  letter-spacing: 2px;
  line-height: 78px;
  color: #282828;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
  float: right;
}

.col-670 {
  z-index: 1;
}

h2 {
  display: flex;
}

.h2--green {
  color: #52b709;
}

@media only screen and (max-width: 360px) {
  .container .wrapper h2 {
    font-size: 32px;
  }
  .col-410 .wrapper-410 {
    padding: 34px;
  }
}

@media only screen and (max-width: 425px) {
  .it_specialist {
    padding: 15px;
  }

  .container-absolute-it-specialist {
    display: none;
  }

  .container {
    padding: 0;
    width: 100%;
    max-width: 100%;
  }

  .row {
    margin-top: 0;
    display: inline-block
  }

  .wrapper {
    justify-content: start;
  }

  .col-410 {
    margin-right: 0;
    margin-left: 0;
  }

  .wrapper-410 {
    padding: 40px;
  }

  .wrapper h2 {
    display: inline-block;
    font-size: 40px;
    line-height: 48px;
  }

  .col-670 .paragraph {
    margin-left: 0;
  }

  .background-img-green {
    margin-bottom: 20px;
  }

  .background-img-green .heading {
    padding: 40px;
    line-height: 37px;
  }
}
</style>