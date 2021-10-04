<template>
  <header>
    <div class="wrapper-logo">
      <div class="logo">
        <img src="../../assets/img/logo.png" alt="logo">
      </div>
      <div class="logo-subtitle">
        Интернет решения для серьезных компаний
      </div>
    </div>
    <ul class="head-navigation">
      <li class="navigation__item"><a href="#">О нас </a></li>
      <li class="navigation__item"><a href="#">Наши возможности</a></li>
      <li class="navigation__item"><a href="#">Наши проекты</a></li>
      <li class="navigation__item"><a href="#">Контакты</a></li>
    </ul>
    <div class="button-contact">
      <div class="icon-telephone">
        <img src="../../assets/img/icon-tel.png" alt="telephone-icon">
      </div>
      <div class="wrapper-telephone">
        <div class="telephone">
          <a href="tel:+7 (343) 300 90 95">
            +7 (343) 300 90 95
          </a>
        </div>
        <a href="#">обратная связь</a>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header"
}
</script>

<style scoped>
@font-face {
  font-family: "G TEesti Pro Display";
  src: url('../../assets/font/font.otf');
}
@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-ThinItalic.eot');
  src: local('G TEesti Pro Text Thin Italic'), local('../../assets/font/GTEestiProText-ThinItalic'),
  url('../../assets/font/GTEestiProText-ThinItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-ThinItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-ThinItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProText-ThinItalic.ttf') format('truetype');
  font-weight: 100;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-Medium.eot');
  src: local('G TEesti Pro Text Medium'), local('../../assets/font/GTEestiProText-Medium'),
  url('../../assets/font/GTEestiProText-Medium.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-Medium.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-Medium.woff') format('woff'),
  url('../../assets/font/GTEestiProText-Medium.ttf') format('truetype');
  font-weight: 500;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-LightItalic.eot');
  src: local('G TEesti Pro Text Light Italic'), local('../../assets/font/GTEestiProText-LightItalic'),
  url('../../assets/font/GTEestiProText-LightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-LightItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-LightItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProText-LightItalic.ttf') format('truetype');
  font-weight: 300;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-Bold.eot');
  src: local('G TEesti Pro Display Bold'), local('../../assets/font/GTEestiProDisplay-Bold'),
  url('../../assets/font/GTEestiProDisplay-Bold.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-Bold.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-Bold.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-Bold.ttf') format('truetype');
  font-weight: bold;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-Light.eot');
  src: local('G TEesti Pro Text Light'), local('../../assets/font/GTEestiProText-Light'),
  url('../../assets/font/GTEestiProText-Light.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-Light.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-Light.woff') format('woff'),
  url('../../assets/font/GTEestiProText-Light.ttf') format('truetype');
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-MediumItalic.eot');
  src: local('G TEesti Pro Display Medium Italic'), local('../../assets/font/GTEestiProDisplay-MediumItalic'),
  url('../../assets/font/GTEestiProDisplay-MediumItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-MediumItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-MediumItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-MediumItalic.ttf') format('truetype');
  font-weight: 500;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-RegularItalic.eot');
  src: local('G TEesti Pro Text Regular Italic'), local('../../assets/font/GTEestiProText-RegularItalic'),
  url('../../assets/font/GTEestiProText-RegularItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-RegularItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-RegularItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProText-RegularItalic.ttf') format('truetype');
  font-weight: normal;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text Book';
  src: url('../../assets/font/GTEestiProText-Book.eot');
  src: local('G TEesti Pro Text Book'), local('../../assets/font/GTEestiProText-Book'),
  url('../../assets/font/GTEestiProText-Book.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-Book.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-Book.woff') format('woff'),
  url('../../assets/font/GTEestiProText-Book.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-BoldItalic.eot');
  src: local('G TEesti Pro Text Bold Italic'), local('../../assets/font/GTEestiProText-BoldItalic'),
  url('../../assets/font/GTEestiProText-BoldItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-BoldItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-BoldItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProText-BoldItalic.ttf') format('truetype');
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-UltraLightItalic.eot');
  src: local('G TEesti Pro Text UltraLight Italic'), local('../../assets/font/GTEestiProText-UltraLightItalic'),
  url('../../assets/font/GTEestiProText-UltraLightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-UltraLightItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-UltraLightItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProText-UltraLightItalic.ttf') format('truetype');
  font-weight: 200;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-Thin.eot');
  src: local('G TEesti Pro Display Thin'), local('../../assets/font/GTEestiProDisplay-Thin'),
  url('../../assets/font/GTEestiProDisplay-Thin.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-Thin.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-Thin.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-Thin.ttf') format('truetype');
  font-weight: 100;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-Regular.eot');
  src: local('G TEesti Pro Text Regular'), local('../../assets/font/GTEestiProText-Regular'),
  url('../../assets/font/GTEestiProText-Regular.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-Regular.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-Regular.woff') format('woff'),
  url('../../assets/font/GTEestiProText-Regular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-Light.eot');
  src: local('G TEesti Pro Display Light'), local('../../assets/font/GTEestiProDisplay-Light'),
  url('../../assets/font/GTEestiProDisplay-Light.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-Light.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-Light.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-Light.ttf') format('truetype');
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-UltraBold.eot');
  src: local('G TEesti Pro Display UltraBold'), local('../../assets/font/GTEestiProDisplay-UltraBold'),
  url('../../assets/font/GTEestiProDisplay-UltraBold.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-UltraBold.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-UltraBold.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-UltraBold.ttf') format('truetype');
  font-weight: 800;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-UltraBoldItalic.eot');
  src: local('G TEesti Pro Display UltraBold Italic'), local('../../assets/font/GTEestiProDisplay-UltraBoldItalic'),
  url('../../assets/font/GTEestiProDisplay-UltraBoldItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-UltraBoldItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-UltraBoldItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-UltraBoldItalic.ttf') format('truetype');
  font-weight: 800;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-Medium.eot');
  src: local('G TEesti Pro Display Medium'), local('../../assets/font/GTEestiProDisplay-Medium'),
  url('../../assets/font/GTEestiProDisplay-Medium.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-Medium.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-Medium.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-Medium.ttf') format('truetype');
  font-weight: 500;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-UltraLight.eot');
  src: local('G TEesti Pro Display UltraLight'), local('../../assets/font/GTEestiProDisplay-UltraLight'),
  url('../../assets/font/GTEestiProDisplay-UltraLight.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-UltraLight.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-UltraLight.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-UltraLight.ttf') format('truetype');
  font-weight: 200;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-RegularItalic.eot');
  src: local('G TEesti Pro Display Regular Italic'), local('../../assets/font/GTEestiProDisplay-RegularItalic'),
  url('../../assets/font/GTEestiProDisplay-RegularItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-RegularItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-RegularItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-RegularItalic.ttf') format('truetype');
  font-weight: normal;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-LightItalic.eot');
  src: local('G TEesti Pro Display Light Italic'), local('../../assets/font/GTEestiProDisplay-LightItalic'),
  url('../../assets/font/GTEestiProDisplay-LightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-LightItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-LightItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-LightItalic.ttf') format('truetype');
  font-weight: 300;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-Bold.eot');
  src: local('G TEesti Pro Text Bold'), local('../../assets/font/GTEestiProText-Bold'),
  url('../../assets/font/GTEestiProText-Bold.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-Bold.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-Bold.woff') format('woff'),
  url('../../assets/font/GTEestiProText-Bold.ttf') format('truetype');
  font-weight: bold;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-Thin.eot');
  src: local('G TEesti Pro Text Thin'), local('../../assets/font/GTEestiProText-Thin'),
  url('../../assets/font/GTEestiProText-Thin.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-Thin.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-Thin.woff') format('woff'),
  url('../../assets/font/GTEestiProText-Thin.ttf') format('truetype');
  font-weight: 100;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-UltraLightItalic.eot');
  src: local('G TEesti Pro Display UltraLight Italic'), local('../../assets/font/GTEestiProDisplay-UltraLightItalic'),
  url('../../assets/font/GTEestiProDisplay-UltraLightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-UltraLightItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-UltraLightItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-UltraLightItalic.ttf') format('truetype');
  font-weight: 200;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-BoldItalic.eot');
  src: local('G TEesti Pro Display Bold Italic'), local('../../assets/font/GTEestiProDisplay-BoldItalic'),
  url('../../assets/font/GTEestiProDisplay-BoldItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-BoldItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-BoldItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-BoldItalic.ttf') format('truetype');
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-MediumItalic.eot');
  src: local('G TEesti Pro Text Medium Italic'), local('../../assets/font/GTEestiProText-MediumItalic'),
  url('../../assets/font/GTEestiProText-MediumItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-MediumItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-MediumItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProText-MediumItalic.ttf') format('truetype');
  font-weight: 500;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text Book';
  src: url('../../assets/font/GTEestiProText-BookItalic.eot');
  src: local('G TEesti Pro Text Book Italic'), local('../../assets/font/GTEestiProText-BookItalic'),
  url('../../assets/font/GTEestiProText-BookItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-BookItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-BookItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProText-BookItalic.ttf') format('truetype');
  font-weight: normal;
  font-style: italic;
}

@font-face {
  font-family: 'G TEesti Pro Text';
  src: url('../../assets/font/GTEestiProText-UltraLight.eot');
  src: local('G TEesti Pro Text UltraLight'), local('../../assets/font/GTEestiProText-UltraLight'),
  url('../../assets/font/GTEestiProText-UltraLight.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProText-UltraLight.woff2') format('woff2'),
  url('../../assets/font/GTEestiProText-UltraLight.woff') format('woff'),
  url('../../assets/font/GTEestiProText-UltraLight.ttf') format('truetype');
  font-weight: 200;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-Regular.eot');
  src: local('G TEesti Pro Display Regular'), local('../../assets/font/GTEestiProDisplay-Regular'),
  url('../../assets/font/GTEestiProDisplay-Regular.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-Regular.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-Regular.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-Regular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'G TEesti Pro Display';
  src: url('../../assets/font/GTEestiProDisplay-ThinItalic.eot');
  src: local('G TEesti Pro Display Thin Italic'), local('../../assets/font/GTEestiProDisplay-ThinItalic'),
  url('../../assets/font/GTEestiProDisplay-ThinItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/font/GTEestiProDisplay-ThinItalic.woff2') format('woff2'),
  url('../../assets/font/GTEestiProDisplay-ThinItalic.woff') format('woff'),
  url('../../assets/font/GTEestiProDisplay-ThinItalic.ttf') format('truetype');
  font-weight: 100;
  font-style: italic;
}

header {
  background-color: #f4f7f7;
  display: flex;
  align-items: center;
  padding: 42px 385px;
  justify-content: space-between;
}

.wrapper-logo {
  display: flex;
  align-items: center;
}

.logo-subtitle {
  text-align: left;
}
.logo {
  padding-right: 20px;
}

.navigation__item {
  list-style-type: none;
}

.navigation__item a {
  text-decoration: none;
}

.head-navigation {
  display: flex;
}

.logo-subtitle {
  font-family: "G TEesti Pro Display";
  width: 110px;
  font-size: 10px;
  letter-spacing: 0px;
  line-height: 11px;
  color: #030303;
}

.wrapper-telephone {
  text-align: left;
}

.icon-telephone img {
  margin: auto;
}

.telephone a {
  text-decoration: none;
  font-size: 14px;
  letter-spacing: 0px;
  color: #454545 !important;
  font-family: "G TEesti Pro Display";
  font-weight: bold;
}

.button-contact {
  display: flex;
  border: 1px solid rgb(255 255 255);
  padding: 5px;
  border-radius: 18px;
  align-items: center;
  background-color: #fff;
  padding-right: 40px;
}

.navigation__item a {
  margin: 0 21px;
  font-size: 16px;
  line-height: 71px;
  color: #1f1e1d;
  font-family: "G TEesti Pro Display";
  font-weight: 500;
}

.icon-telephone {
  background-color: blue;
  width: 30px;
  border-radius: 50%;
  height: 30px;
  display: flex;
  margin-right: 12px;
}

.wrapper-telephone a {
  font-size: 12px;
  letter-spacing: 1px;
  line-height: 13px;
  color: #a6a5a5;
  font-family: "G TEesti Pro Display";
}
</style>