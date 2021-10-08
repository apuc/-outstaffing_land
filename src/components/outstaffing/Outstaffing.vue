<template>
  <section class="outstaffing">
    <img class="background-circle" src="../../assets/img/circle-background.png" alt="background-circle">
    <h2 class="z-index-1">RUBY ON RAIlS - PHP - PYTHON - VUE.JS - REACT. JS</h2>
    <div class="container">
      <img class="arrow-right-top" src="../../assets/img/arrow-right-top.png" alt="arrow-right-top">
      <h1>
        <div class="h1--black">IT</div>
        &nbsp;АУТСТАФИНГ
      </h1>
      <div class="wrapper">
        <div class="paragraph">
          Подберем и документально оформим IT-специалистов, после чего передадим исполнителей под ваше руководство. Вы
          получаете полное управление над сотрудниками, имея возможность контролировать и заменять IT штат.
        </div>
        <button class="autorization">
          Войти
        </button>
      </div>
      <div class="container-absolute-outstaffing">
        <img class="img-1" src="../../assets/img/main-image/1.png" alt="1">
        <img class="img-2" src="../../assets/img/main-image/2.png" alt="2">
        <img class="img-3" src="../../assets/img/main-image/3.png" alt="3">
        <img class="img-4" src="../../assets/img/main-image/4.png" alt="4">
        <img class="img-5" src="../../assets/img/main-image/5.png" alt="5">
        <img class="img-6" src="../../assets/img/main-image/6.png" alt="6">
        <img class="img-7" src="../../assets/img/main-image/7.png" alt="7">
        <img class="img-8" src="../../assets/img/main-image/8.png" alt="8">
        <img class="img-9" src="../../assets/img/main-image/9.png" alt="9">
      </div>
    </div>
  </section>
</template>

<script>
import ScrollReveal from 'scrollreveal';
import {CONFIG_IMG_SHOW} from "../../../constants/config";

export default {
  name: "Outstaffing",
  methods: {
    getScroll: function () {
      for (let i = 1; i < 10; i++) {
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
.outstaffing {
  background-color: #f4f7f7;
  padding-top: 95px;
}

.container-absolute-outstaffing .img-1 {
  z-index: -1;
}

.container-absolute-outstaffing {
  position: absolute;
  top: 32px;
  left: 135px;
  z-index: 10;
}

.img-1, .img-2, .img-3, .img-4, .img-5, .img-6, .img-7, .img-8, .img-9 {
  position: absolute;
  z-index: 1;
}

.img-1 {
  top: 0;
  left: 0;
}

.img-2 {
  top: 313px;
  left: 299px;
}

.img-3 {
  top: 368px;
  left: 599px;
}

.img-4 {
  top: 393px;
  left: 5px;
}

.img-5 {
  top: 493px;
  left: 440px;
}

.img-6 {
  top: 483px;
  left: 239px;
}

.img-7 {
  top: 488px;
  left: 170px;
}

.img-8 {
  top: 505px;
  left: 334px;
}

.img-9 {
  top: 636px;
  left: 498px;
}

button:not(:disabled) {
  cursor: pointer;
}

button:hover {
  background-image: none;
  background-color: #ffffff;
  border: 2px solid #6aaf5c;
  color: #6aaf5c !important;
  transition: .3s;
}

.autorization {
  margin-top: 83px;
  width: 268px;
  height: 75px;
  box-shadow: 6px 5px 20px rgb(82, 151, 34, 0.21);
  border-radius: 38px;
  background-color: #fff;
  background-image: linear-gradient(
      0deg, #6aaf5c 0, #52b709), linear-gradient(
      36deg, hsla(0, 0%, 100%, 0), hsla(0, 0%, 100%, .16) 47%, hsla(0, 0%, 100%, .17) 50%, hsla(0, 0%, 100%, 0));
  color: #fff;
  font-family: "Muller", serif;
  font-weight: 700;
  font-size: 2.2em;
  letter-spacing: normal;
  line-height: 71.88px;
  text-align: center;
  border: 2px solid #6aaf5c;
  margin-right: 1.5rem;
}

.container {
  position: relative;
}

.wrapper {
  width: 100%;
  display: inline-grid;
  justify-content: flex-end;
  padding-bottom: 97px;
}

img.background-circle {
  position: absolute;
  left: -177px;
  top: 96px;
  z-index: 0;
}

.arrow-right-top {
  position: absolute;
  top: 60px;
  left: 140px;
}

h1 {
  font-family: "GT Eesti Pro Display", serif;
  display: flex;
  margin-left: 830px;
  font-size: 120px;
  line-height: 249px;
  font-weight: bold;
  color: #4caf50;
}

.paragraph {
  padding-left: 15px;
  font-size: 26px;
  line-height: 29px;
  color: #000000;
  font-family: "GT Eesti Pro Display", serif;
  max-width: 650px;
  float: right;
  margin-right: 280px;
  text-align: left;
  margin-left: auto;
}

.h1--black {
  color: #000;
}

.z-index-1 {
  z-index: 1;
}

h2 {
  font-size: 52px;
  letter-spacing: 10px;
  line-height: 60px;
  color: #c3c5c5;
  margin-bottom: 0;
  margin-top: 0;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
  text-align: center;
}

@media only screen and (max-width: 768px) {
  .outstaffing {
    padding-top: 50px;
    padding-left:19px;
    padding-right: 19px;
    background-color: #ffffff;
  }
  .container-absolute-outstaffing {
    display: block;
    width: 100%;
    height: 160px;
    position: relative;
    top: 0;
    left: 0;
  }

  img.img-1 {
    width: 233px;
    height: 236px;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 0;
  }
  img.img-2 {
    top: 105px;
    left: 50%;
    right: 50%;
    transform: translate(-53px, -50%);
    width: 16px;
    height: 19px;
  }
  img.img-3 {
    top: 84px;
    left: 50%;
    right: 50%;
    transform: translate(53px, -50%);
    width: 42px;
    height: 40px;
  }
  img.img-4 {
    top: 111px;
    left: 50%;
    right: 50%;
    transform: translate(-116px, -50%);
    width: 55px;
    height: 70px;
  }
  img.img-5 {
    top: 105px;
    left: 50%;
    right: 50%;
    transform: translate(-67px, -50%);
    width: 7px;
    height: 10px;
  }
  img.img-6 {
    top: 61px;
    left: 50%;
    right: 50%;
    transform: translate(-24px, -50%);
    width: 15px;
    height: 20px;
  }
  img.img-7 {
    top: 105px;
    left: 50%;
    right: 50%;
    transform: translate(13px, -50%);
    width: 8px;
    height: 13px;
  }
  img.img-8 {
    top: 133px;
    left: 50%;
    right: 50%;
    transform: translate(-14px, -50%);
    width: 45px;
    height: 50px;
  }
  img.img-9 {
    top: 165px;
    left: 50%;
    right: 50%;
    transform: translate(30px, -50%);
    width: 30px;
    height: 30px;
  }

  .arrow-right-top {
    /*display: none;*/
    display: block;
    position: relative;
    top: 0;
    left: 50%;
    right: 50%;
    transform: translate(-50%, -50%);
    width: 22px;
    height: 22px;
  }

  h1 {
    justify-content: center;
    margin-left: 0;
    line-height: 60px;
    font-size: 34px;
    margin-bottom: 25px;
  }

  h2 {
    display: none;
    font-size: 42px;
    line-height: 35px;
  }

  .paragraph {
    margin-right: 0;
    padding: 0;
    font-size: 16px;
    font-weight: 400;
    line-height: 22px;
    text-align: center;
  }

  button {
    margin: 40px auto 0 auto;
  }

  .autorization {
    margin: 32px auto;
    padding: 0;
    width: 192px;
    height: 50px;
    color: #ffffff;
    font-family: "Muller Extra Bold";
    font-size: 15px;
    font-weight: 400;
    line-height: 47.92px;
    letter-spacing: 1.1px;
    z-index: 15;
  }

  img.background-circle {
    display: none;
  }

  .wrapper {
    padding-bottom: 0;
    display: flex;
    flex-wrap: wrap;
  }
}
</style>