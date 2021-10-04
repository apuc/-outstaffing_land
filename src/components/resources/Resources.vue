<template>
  <section class="resources-and-technology">
    <img class="background-right" src="../../assets/img/background-right.png" alt="right">
    <div class="container-background-white">
      <div class="wrapper">
        <div class="align-left-container">
          <h2>Ресурсы и технологии</h2>
          <div class="h2-paragraph">Подключение от 3 дней. Более 300 специалистов в штате</div>
        </div>
        <div class="row">
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Laravel.png" alt="Laravel">
              <div class="paragraph">PHP Framework<br> For Web Artisans</div>
            </div>
          </div>
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Vue.png" alt="Vue">
              <div class="paragraph">Прогрессивный<br> JavaScript-фреймворк.</div>
            </div>
          </div>
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Ux.png" alt="Ux">
              <div class="paragraph">Дизайн взаимодействия<br> с пользователем</div>
            </div>
          </div>
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Digital.png" alt="Digital">
              <div class="paragraph">Комплексный инфлюенс<br> маркетинг</div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="wrapper-lang">
            <p>Ruby on Rails</p>
            <p>Php</p>
            <p>Python</p>
            <p>VueJS</p>
            <p>React.js</p>
          </div>
          <div class="wrapper-lang">
            <p>Djungo</p>
            <p>Flask</p>
            <p>Pyramid</p>
          </div>
          <div class="wrapper-lang">
            <p>Cto</p>
            <p>Manager</p>
          </div>
          <div class="wrapper-lang">
            <p>Sql</p>
            <p>Mysql</p>
            <p>Redis</p>
            <p>Ealm</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Resources"
}
</script>

<style scoped>
.wrapper-lang {
  padding-left: 38px;
  text-align: left;
  flex: 1;
}

.wrapper {
  width: 1190px;
  padding-bottom: 60px;
}

.row:last-child {
  display: flex;
  width: 1105px;
  flex: 1;
  margin-top: 30px;
  margin-left: 85px;
  justify-content: space-between;
}

.background-right {
  position: absolute;
  right: -240px;
  top: 1680px;
}

.align-left-container {
  display: inline-block;
  margin-left: 140px;
}

.col-3 {
  display: flex;
  text-align: center;
  position: relative;
  z-index: 0;
}

.wrapper-lang p {
  text-decoration: underline;
  text-transform: uppercase;
  font-size: 25px;
  letter-spacing: -1px;
  margin-bottom: 40px;
  color: #1f1f1f;
  font-family: "G TEesti Pro Display";
  font-weight: bold;
}

.wrapper-col {
  border: 0.29px solid #d4d4d4;
  background-color: #fafafb;
  padding: 60px 40px;
  text-align: left;
}

.col-3:first-child::before {
  content: '';
  display: block;
  height: 3px;
  width: 103px;
  position: absolute;
  right: -1px;
  top: -3px;
  background: green;
}

.row {
  display: flex;
  justify-content: space-between;
  max-width: 1190px;
  margin-left: 85px;
  margin-top: 120px;
}

.col-3 p {
  font-size: 25px;
  letter-spacing: -1px;
  color: #1f1f1f;
  font-family: "G TEesti Pro Display";
  font-weight: bold;
}

.col-3 .paragraph {
  font-size: 19px;
  line-height: 29px;
  color: #0f0000;
  font-family: "G TEesti Pro Display";
  padding-top: 38px;
}

.col-3:nth-child(3)::before {
  content: '';
  display: block;
  height: 3px;
  width: 100%;
  position: absolute;
  right: -1px;
  top: -3px;
  background: green;
}

.col-3:nth-child(2n+1) {
  margin-top: 10px;
}

.resources-and-technology {
  background-color: #f4f7f7;
  display: grid;
}

.container-background-white {
  background-image: url("../../assets/img/background-white.png");
  text-align: center;
}

.h2-paragraph {
  margin-left: 490px;
}

.paragraph, .h2-paragraph {
  font-size: 20px;
  color: #0f0000;
  font-family: "G TEesti Pro Display";
  font-weight: 300;
  max-width: 313px;
  text-align: left;
  margin: auto;
}

h2 {
  margin-top: 230px;
  max-width: 272px;
  text-align: left;
  font-size: 50px;
  letter-spacing: 2px;
  line-height: 50px;
  color: #282828;
  font-family: "G TEesti Pro Display";
  font-weight: bold;
}
</style>