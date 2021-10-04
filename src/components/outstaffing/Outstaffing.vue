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
        <div class="autorization">
          Войти
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Outstaffing"
}
</script>

<style scoped>
.outstaffing {
  background-color: #f4f7f7;
  position: relative;
  padding-top: 95px;
}

.container {
  position: relative;
}

.wrapper {
  width: 100%;
  display: inline-grid;
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

.autorization {
  width: 290px;
  height: 75px;
  border-radius: 37px;

  box-shadow: 4px 7px 20px rgba(82, 151, 34, 0.21);
  background-image: url("../../assets/img/button.png");
  background-repeat: no-repeat;
  float: right;
  margin-right: 660px;
  margin-top: 80px;
  margin-left: auto;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 22px;
  letter-spacing: 1px;
  color: #ffffff;
  font-family: "Muller Extra Bold";
  font-weight: 800;

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