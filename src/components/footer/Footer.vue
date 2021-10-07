<template>
  <footer class="footer">
    <div class="wrapper-telephone">
      <div class="telephone__title">
        Горячая линия
      </div>
      <a href="tel:89451567898">
        8 945 156 78 98
      </a>
    </div>
    <div class="about-us">
      Но акционеры крупнейших компаний формируют глобальную экономическую сеть и при этом - ассоциативно распределены по
      отростям Противоложная точка зрения подразумевает
    </div>
  </footer>
</template>

<script>
export default {
  name: "Footer"
}
</script>

<style scoped>
.footer {
  display: flex;
  justify-content: space-between;
  padding: 25px 285px;
  align-items: center;
  background-color: #202020;
}

.telephone__title, .wrapper-telephone a {
  text-align: left;
  font-size: 21px;
  line-height: 47px;
  color: #ffffff;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
}

.wrapper-telephone a {
  font-size: 50px;
  text-decoration: none;
}

.about-us {
  font-size: 20px;
  color: #ffffff;
  width: 64%;
  font-family: "GT Eesti Pro Display", serif;
  font-weight: bold;
  text-align: left;
}

@media only screen and (min-width:320px) and (max-width: 360px) {
  .wrapper-telephone {
    font-size: 40px;
  }
}

@media only screen and (min-width: 320px) and (max-width: 768px) {
  .footer {
    padding: 15px;
    display: block;
  }

  .telephone__title {
    text-align: center;
  }

  .about-us {
    width: 100%;
    padding: 15px 0;
    text-align: center;
  }

}
</style>