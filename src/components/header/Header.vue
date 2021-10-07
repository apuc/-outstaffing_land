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
    <div class="mobile-nav">
      <div
          class="btn-nav-open"
          v-on:click="open_nav_menu"
      >
        <svg width="25" height="25" viewBox="0 0 48 48" fill="none" xmlns="http://www.w3.org/2000/svg">
          <rect width="48" height="48" fill="white" fill-opacity="0.01"/>
          <path d="M7.94977 11.9498H39.9498" stroke="black" stroke-width="4" stroke-linecap="round"
                stroke-linejoin="round"/>
          <path d="M7.94977 23.9498H39.9498" stroke="black" stroke-width="4" stroke-linecap="round"
                stroke-linejoin="round"/>
          <path d="M7.94977 35.9498H39.9498" stroke="black" stroke-width="4" stroke-linecap="round"
                stroke-linejoin="round"/>
        </svg>
      </div>
      <div
          v-if="show_nav_menu"
          ref="nav_menu"
          class="nav-menu">
        <a href="#">О нас</a>
        <a href="#">Наши возможности</a>
        <a href="#">Наши проекты</a>
        <a href="#">Контакты</a>
      </div>

    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      show_nav_menu: false
    }
  },
  methods: {
    open_nav_menu: function () {
      this.show_nav_menu = !this.show_nav_menu
    }
  }
}
</script>

<style scoped>
.mobile-nav {
  display: none;
  position: relative;
}

.mobile-nav .nav-menu {
  position: absolute;
  top: 30px;
  right: 0;
  display: inline-grid;
  background-color: #efeff5;;
  width: 150px;
  text-align: right;
  padding: 10px;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-ThinItalic.eot');
  src: local('GT Eesti Pro Text Thin Italic'), local('../../assets/font/GTEestiProText-ThinItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProText-ThinItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-ThinItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-ThinItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-ThinItalic.ttf') format('truetype');
  font-weight: 100;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-Medium.eot');
  src: local('GT Eesti Pro Text Medium'), local('../../assets/font/GTEestiProText-Medium'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Medium.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Medium.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Medium.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Medium.ttf') format('truetype');
  font-weight: 500;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-LightItalic.eot');
  src: local('GT Eesti Pro Text Light Italic'), local('../../assets/font/GTEestiProText-LightItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProText-LightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-LightItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-LightItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-LightItalic.ttf') format('truetype');
  font-weight: 300;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-Bold.eot');
  src: local('GT Eesti Pro Display Bold'), local('../../assets/font/GTEestiProDisplay-Bold'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Bold.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Bold.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Bold.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Bold.ttf') format('truetype');
  font-weight: bold;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-Light.eot');
  src: local('GT Eesti Pro Text Light'), local('../../assets/font/GTEestiProText-Light'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Light.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Light.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Light.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Light.ttf') format('truetype');
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-MediumItalic.eot');
  src: local('GT Eesti Pro Display Medium Italic'), local('../../assets/font/GTEestiProDisplay-MediumItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-MediumItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-MediumItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-MediumItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-MediumItalic.ttf') format('truetype');
  font-weight: 500;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-RegularItalic.eot');
  src: local('GT Eesti Pro Text Regular Italic'), local('../../assets/font/GTEestiProText-RegularItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProText-RegularItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-RegularItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-RegularItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-RegularItalic.ttf') format('truetype');
  font-weight: normal;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text Book';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-Book.eot');
  src: local('GT Eesti Pro Text Book'), local('../../assets/font/GTEestiProText-Book'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Book.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Book.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Book.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Book.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-BoldItalic.eot');
  src: local('GT Eesti Pro Text Bold Italic'), local('../../assets/font/GTEestiProText-BoldItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BoldItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BoldItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BoldItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BoldItalic.ttf') format('truetype');
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-UltraLightItalic.eot');
  src: local('GT Eesti Pro Text UltraLight Italic'), local('../../assets/font/GTEestiProText-UltraLightItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLightItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLightItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLightItalic.ttf') format('truetype');
  font-weight: 200;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-Thin.eot');
  src: local('GT Eesti Pro Display Thin'), local('../../assets/font/GTEestiProDisplay-Thin'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Thin.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Thin.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Thin.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Thin.ttf') format('truetype');
  font-weight: 100;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-Regular.eot');
  src: local('GT Eesti Pro Text Regular'), local('../../assets/font/GTEestiProText-Regular'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Regular.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Regular.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Regular.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Regular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-Light.eot');
  src: local('GT Eesti Pro Display Light'), local('../../assets/font/GTEestiProDisplay-Light'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Light.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Light.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Light.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Light.ttf') format('truetype');
  font-weight: 300;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBold.eot');
  src: local('GT Eesti Pro Display UltraBold'), local('../../assets/font/GTEestiProDisplay-UltraBold'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBold.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBold.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBold.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBold.ttf') format('truetype');
  font-weight: 800;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBoldItalic.eot');
  src: local('GT Eesti Pro Display UltraBold Italic'), local('../../assets/font/GTEestiProDisplay-UltraBoldItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBoldItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBoldItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBoldItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraBoldItalic.ttf') format('truetype');
  font-weight: 800;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-Medium.eot');
  src: local('GT Eesti Pro Display Medium'), local('../../assets/font/GTEestiProDisplay-Medium'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Medium.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Medium.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Medium.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Medium.ttf') format('truetype');
  font-weight: 500;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLight.eot');
  src: local('GT Eesti Pro Display UltraLight'), local('../../assets/font/GTEestiProDisplay-UltraLight'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLight.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLight.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLight.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLight.ttf') format('truetype');
  font-weight: 200;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-RegularItalic.eot');
  src: local('GT Eesti Pro Display Regular Italic'), local('../../assets/font/GTEestiProDisplay-RegularItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-RegularItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-RegularItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-RegularItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-RegularItalic.ttf') format('truetype');
  font-weight: normal;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-LightItalic.eot');
  src: local('GT Eesti Pro Display Light Italic'), local('../../assets/font/GTEestiProDisplay-LightItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-LightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-LightItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-LightItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-LightItalic.ttf') format('truetype');
  font-weight: 300;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-Bold.eot');
  src: local('GT Eesti Pro Text Bold'), local('../../assets/font/GTEestiProText-Bold'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Bold.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Bold.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Bold.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Bold.ttf') format('truetype');
  font-weight: bold;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-Thin.eot');
  src: local('GT Eesti Pro Text Thin'), local('../../assets/font/GTEestiProText-Thin'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Thin.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Thin.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Thin.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-Thin.ttf') format('truetype');
  font-weight: 100;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLightItalic.eot');
  src: local('GT Eesti Pro Display UltraLight Italic'), local('../../assets/font/GTEestiProDisplay-UltraLightItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLightItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLightItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLightItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-UltraLightItalic.ttf') format('truetype');
  font-weight: 200;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-BoldItalic.eot');
  src: local('GT Eesti Pro Display Bold Italic'), local('../../assets/font/GTEestiProDisplay-BoldItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-BoldItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-BoldItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-BoldItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-BoldItalic.ttf') format('truetype');
  font-weight: bold;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-MediumItalic.eot');
  src: local('GT Eesti Pro Text Medium Italic'), local('../../assets/font/GTEestiProText-MediumItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProText-MediumItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-MediumItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-MediumItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-MediumItalic.ttf') format('truetype');
  font-weight: 500;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text Book';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-BookItalic.eot');
  src: local('GT Eesti Pro Text Book Italic'), local('../../assets/font/GTEestiProText-BookItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BookItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BookItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BookItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-BookItalic.ttf') format('truetype');
  font-weight: normal;
  font-style: italic;
}

@font-face {
  font-family: 'GT Eesti Pro Text';
  src: url('../../assets/fonts/GTEesti/GTEestiProText-UltraLight.eot');
  src: local('GT Eesti Pro Text UltraLight'), local('../../assets/font/GTEestiProText-UltraLight'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLight.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLight.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLight.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProText-UltraLight.ttf') format('truetype');
  font-weight: 200;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-Regular.eot');
  src: local('GT Eesti Pro Display Regular'), local('../../assets/font/GTEestiProDisplay-Regular'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Regular.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Regular.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Regular.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-Regular.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

@font-face {
  font-family: 'GT Eesti Pro Display';
  src: url('../../assets/fonts/GTEesti/GTEestiProDisplay-ThinItalic.eot');
  src: local('GT Eesti Pro Display Thin Italic'), local('../../assets/font/GTEestiProDisplay-ThinItalic'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-ThinItalic.eot?#iefix') format('embedded-opentype'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-ThinItalic.woff2') format('woff2'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-ThinItalic.woff') format('woff'),
  url('../../assets/fonts/GTEesti/GTEestiProDisplay-ThinItalic.ttf') format('truetype');
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

.nav-menu a {
  text-decoration: none;
  color: #4caf50;
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
  font-family: "GT Eesti Pro Display";
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
  font-family: "GT Eesti Pro Display";
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
  font-family: "GT Eesti Pro Display";
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
  font-family: "GT Eesti Pro Display";
}

@media only screen and (max-width: 425px) {
  header {
    padding: 15px;
  }

  .head-navigation {
    display: none;
  }

  .logo-subtitle {
    display: none;
  }

  .button-contact {
    display: none;
  }

  .mobile-nav {
    display: flex;
  }
}
</style>