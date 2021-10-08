<template>
  <section class="our-advantages">
    <img class="arrow-right-top" src="../../assets/img/arrow-right-top.png" alt="arrow-right-top">
    <div class="container-absolute-our-advantages">
      <img src="../../assets/img/4block/1.png" alt="" class="img-1">
      <img src="../../assets/img/4block/2.png" alt="" class="img-2">
      <img src="../../assets/img/4block/3.png" alt="" class="img-3">
    </div>
    <div class="container">
      <h2>Наши преимущества</h2>
      <div class="row">
        <div class="col-6">
          <div class="wrapper-img">
            <img src="../../assets/img/plus.png" alt="plus">
          </div>
          <div class="wrapper-content">
            <div class="title">
              Быстро и качественно
            </div>
            <div class="paragraph">
              В среднем вакансии закрываем за
              2-3 недели. Направляем только
              релевантные резюме
              заинтересованных кандидатов.
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="wrapper-img">
            <img src="../../assets/img/plus.png" alt="plus">
          </div>
          <div class="wrapper-content">
            <div class="title">
              Быстро и качественно
            </div>
            <div class="paragraph">
              В среднем вакансии закрываем за
              2-3 недели. Направляем только
              релевантные резюме
              заинтересованных кандидатов.
            </div>
          </div>
        </div>
      </div>
      <div class="row">
        <div class="col-6">
          <div class="wrapper-img">
            <img src="../../assets/img/plus.png" alt="plus">
          </div>
          <div class="wrapper-content">
            <div class="title">
              Быстро и качественно
            </div>
            <div class="paragraph">
              В среднем вакансии закрываем за
              2-3 недели. Направляем только
              релевантные резюме
              заинтересованных кандидатов.
            </div>
          </div>
        </div>
        <div class="col-6">
          <div class="wrapper-img">
            <img src="../../assets/img/plus.png" alt="plus">
          </div>
          <div class="wrapper-content">
            <div class="title">
              Быстро и качественно
            </div>
            <div class="paragraph">
              В среднем вакансии закрываем за
              2-3 недели. Направляем только
              релевантные резюме
              заинтересованных кандидатов.
            </div>
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
  name: "OurAdvantages",
  methods: {
    getScroll: function () {
      for (let i = 1; i < 4; i++) {
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
.container-absolute-our-advantages {
  position: absolute;
  top: 0;
  right: 0;
}

.img-1, .img-2, .img-3 {
  position: absolute;
  z-index: 1;
}

.img-1 {
  top: 30px;
  right: 97px;
  z-index: 1;
}

.img-2 {
  top: 135px;
  right: 241px;
}

.img-3 {
  top: 377px;
  right: 393px;
  z-index: 0;
}

.our-advantages {
  position: relative;
  background-color: #f5f5f6;
  display: grid;
}

.arrow-right-top {
  position: absolute;
  top: -30px;
  left: 185px;
  overflow: hidden !important;
}

.container {
  max-width: 880px;
  margin-left: 130px;
}

.row {
  display: flex;
  justify-content: space-between;
}

h2 {
  margin-bottom: 70px;
  padding-top: 26px;
  font-size: 50px;
  letter-spacing: 2px;
  line-height: 50px;
  color: #282828;
  font-weight: bold;
}

.row + .row {
  padding-top: 86px;
}

.title {
  margin-top: 25px;
  font-size: 23px;
  color: #0f0000;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
  margin-bottom: 39px;
}

.paragraph {
  font-size: 20px;
  color: #0f0000;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: 300;
  max-width: 290px;
}

.col-6 {
  display: flex;
  text-align: left;
}

.wrapper-content {
  margin-left: 30px;
}

@media only screen and (min-width: 1601px) and (max-width : 1919px) {}
@media only screen and (min-width: 1201px) and (max-width : 1600px) {}

@media only screen and (min-width: 1025px) and (max-width : 1200px)  {
  .container {
    padding: 30px;
    margin-left: 0;
  }
}
@media only screen and (min-width: 768px) and (max-width : 1024px)  {}
@media only screen and (min-width: 320px) and (max-width : 768px)  {
  .our-advantages {
    padding: 15px;
  }

  .container-absolute-our-advantages {
    display: none;
  }

  .container {
    margin: 0;
  }

  .row + .row {
    padding-top: 0;
  }

  .row {
    display: flex;
    flex-wrap: wrap;
  }

  h2 {
    font-size: 36px;
  }

  .col-6 {
    padding: 20px 0;
    max-width: 340px;
  }

  .title {
    margin-top: 0;
    margin-bottom: 20px;
  }

  .arrow-right-top {
    top: -10px;
    left: 10px;
  }
}
</style>