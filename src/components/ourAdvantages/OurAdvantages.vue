<template>
  <section class="our-advantages">
    <img class="arrow-right-top" src="../../assets/img/arrow-right-top.png" alt="arrow-right-top">
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
export default {
  name: "OurAdvantages"
}
</script>

<style scoped>
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
  font-family: "G TEesti Pro Display";
  font-weight: bold;
  margin-bottom: 39px;
}

.paragraph {
  font-size: 20px;
  color: #0f0000;
  font-family: "G TEesti Pro Display";
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
</style>