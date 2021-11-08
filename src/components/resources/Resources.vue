<template>
  <section class="resources-and-technology">
    <div class="container-absolute-resources">
      <img
        class="background-right"
        src="../../assets/img/background-right.png"
        alt="right"
      />
      <img src="../../assets/img/main-image/19.png" alt="" class="img-1" />
      <img src="../../assets/img/main-image/20.png" alt="" class="img-2" />
      <img src="../../assets/img/main-image/21.png" alt="" class="img-3" />
      <img src="../../assets/img/main-image/22.png" alt="" class="img-4" />
      <img src="../../assets/img/main-image/23.png" alt="" class="img-5" />
      <img src="../../assets/img/main-image/24.png" alt="" class="img-6" />
      <img src="../../assets/img/main-image/25.png" alt="" class="img-7" />
      <img src="../../assets/img/main-image/26.png" alt="" class="img-8" />
      <img src="../../assets/img/main-image/27.png" alt="" class="img-9" />
    </div>
    <div class="container-background-white">
      <div class="wrapper">
        <div class="align-left-container">
          <h2>Ресурсы и технологии</h2>
          <div class="h2-paragraph">
            Подключение от 3 дней. Более 300 специалистов в штате
          </div>
        </div>
        <div class="row">
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Laravel.png" alt="Laravel" />
              <div class="paragraph">
                PHP Framework<br />
                For Web Artisans
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Vue.png" alt="Vue" />
              <div class="paragraph">
                Прогрессивный<br />
                JavaScript-фреймворк.
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Ux.png" alt="Ux" />
              <div class="paragraph">
                Дизайн взаимодействия<br />
                с пользователем
              </div>
            </div>
          </div>
          <div class="col-3">
            <div class="wrapper-col">
              <img src="../../assets/img/Digital.png" alt="Digital" />
              <div class="paragraph">
                Комплексный инфлюенс<br />
                маркетинг
              </div>
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
import ScrollReveal from "scrollreveal";
import { CONFIG_IMG_SHOW } from "../../../constants/config";

export default {
  name: "Resources",
  methods: {
    getScroll: function () {
      for (let i = 1; i < 10; i++) {
        ScrollReveal().reveal(".img-" + i, CONFIG_IMG_SHOW);
      }
    },
  },
  mounted() {
    this.getScroll();
  },
};
</script>

<style scoped>
.resources-and-technology {
  position: relative;
}

.container-absolute-resources,
.img-1,
.img-2,
.img-3,
.img-4,
.img-5,
.img-6,
.img-7,
.img-8,
.img-9 {
  position: absolute;
}

.container-absolute-resources {
  top: 0;
  right: 0;
}

.img-2,
.img-3,
.img-4,
.img-5,
.img-6,
.img-7,
.img-8,
.img-9 {
  z-index: 1;
}

.img-1 {
  top: 125px;
  right: 149px;
  z-index: 1;
}

.img-2 {
  top: 324px;
  right: 492px;
  z-index: 2;
}

.img-3 {
  top: 245px;
  right: 426px;
  z-index: 1;
}

.img-4 {
  top: 564px;
  right: 57px;
}

.img-5 {
  top: 591px;
  right: 397px;
}

.img-6 {
  top: 726px;
  right: 163px;
}

.img-7 {
  top: 801px;
  right: 367px;
}

.img-8 {
  top: 698px;
  right: 248px;
}

.img-9 {
  top: 1035px;
  right: 318px;
  z-index: 3;
}

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
  z-index: 3;
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
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
}

.wrapper-col {
  border: 0.29px solid #d4d4d4;
  background-color: #fafafb;
  padding: 60px 40px;
  text-align: left;
}

.col-3:first-child::before {
  content: "";
  display: block;
  height: 3px;
  width: 103px;
  position: absolute;
  right: -1px;
  top: -3px;
  background: #4caf50;
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
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
}

.col-3 .paragraph {
  font-size: 19px;
  line-height: 29px;
  color: #0f0000;
  font-family: "GT Eesti Pro Display", serif;
  padding-top: 38px;
}

.col-3:nth-child(3)::before {
  content: "";
  display: block;
  height: 3px;
  width: 100%;
  position: absolute;
  right: -1px;
  top: -3px;
  background: #4caf50;
}

.col-3:nth-child(2n + 1) {
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

.paragraph,
.h2-paragraph {
  font-size: 20px;
  color: #0f0000;
  font-family: "GT Eesti Pro Display", serif;
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
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
}

@media only screen and (max-width: 768px) {
  .resources-and-technology {
    padding: 15px;
    display: block;
    background-color: #ffffff;
  }

  .col-3:nth-child(3)::before {
    height: 8px;
    right: 0px;
    top: 1px;
  }
  .col-3:first-child::before {
    height: 8px;
    right: 0px;
    top: 1px;
  }
  .container-absolute-resources {
    display: none;
  }

  .wrapper-lang {
    display: none;
  }

  h2 {
    margin: auto;
    margin-bottom: 30px;
    font-size: 25px;
    font-weight: 700;
    text-align: center;
    letter-spacing: 0.27px;
  }

  .h2-paragraph {
    font-size: 15px;
    font-weight: 300;
    text-align: center;
  }
  .col-3 .paragraph {
    text-align: left;
    font-size: 17px;
    font-weight: 400;
    font-style: normal;
    letter-spacing: normal;
    line-height: 22.64px;
  }

  .align-left-container {
    margin-left: 0;
  }

  .align-left-container h2 {
    margin-top: 0;
  }

  .wrapper .row {
    display: flex;
    flex-direction: column;
    margin-left: 0;
    margin-top: 30px;
    min-width: 232px;
    padding: 0;
  }

  .row {
    padding: 25px !important;
  }
  .wrapper-col {
    /* min-width: 232px; */
    padding: 20px !important;
  }

  .row .col-3 {
    padding: 0;
  }

  .wrapper-col {
    padding: 60px 40px;
    width: 100%;
    text-align: center;
  }

  .wrapper {
    display: block;
    width: 100%;
    padding-bottom: 25px;
  }

  .wrapper .row {
    margin-top: 3px;
  }
  .row:last-child {
    margin: 0;
    display: none;
    width: 100%;
    background-color: white;
  }

  .col-3 + .col-3 {
    margin-top: 22px;
  }
}
</style>
