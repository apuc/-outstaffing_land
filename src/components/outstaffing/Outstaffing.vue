<template>
  <section class="outstaffing">
    <img class="background-circle" src="../../assets/img/circle-background.png" alt="background-circle">
    <h2 class="z-index-1">RUBY ON RAIlS - PHP - PYTHON - VUE.JS - REACT. JS</h2>
    <div class="container">
      <img class="arrow-right-top" src="../../assets/img/arrow-right-top.png" alt="arrow-right-top">
      <img class="background-img" src="../../assets/img/background-img.png" alt="background-circle">
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
    </div>
  </section>
</template>

<script>
export default {
  name: "Outstaffing",
}
</script>

<style scoped>
.outstaffing {
  background-color: #f4f7f7;
  position: relative;
  padding-top: 95px;
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
      0deg,#6aaf5c 0,#52b709),linear-gradient(
      36deg,hsla(0,0%,100%,0),hsla(0,0%,100%,.16) 47%,hsla(0,0%,100%,.17) 50%,hsla(0,0%,100%,0));
  color: #fff;
  font-family: "Muller";
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
  left: -20px;
  top: -85px;
}

.background-img {
  position: absolute;
  top: 30px;
  left: 45px;
  z-index: 1;
}

.arrow-right-top {
  position: absolute;
  top: 60px;
  left: 140px;
}

h1 {
  font-family: "G TEesti Pro Display";
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
  font-family: "G TEesti Pro Display";
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
  /*padding-bottom: 105px;*/
  margin-bottom: 0;
  margin-top: 0;
  font-family: "G TEesti Pro Display";
  font-weight: bold;
  text-align: center;
}
</style>