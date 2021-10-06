<template>
  <section class="form">
    <div class="row">
      <div class="col-6 mt-170">
        <div class="item-specialist">
          <img src="../../assets/img/15.png" alt="">
          <p>Свободных специалистов</p>
        </div>
        <div class="item-specialist">
          <img src="../../assets/img/15.png" alt="">
          <p>Свободных специалистов</p>
        </div>
        <div class="item-specialist">
          <img src="../../assets/img/15.png" alt="">
          <p>Свободных специалистов</p>
        </div>
      </div>
      <div class="col-6">
        <div class="wrapper-form">
          <div class="send-a-request">
            Отправить запрос
          </div>
          <label for="login">Ваш логин:</label>
          <input id="login" type="text" placeholder="Логин">
          <label for="password">Пароль:</label>
          <input id="password" type="text" placeholder="Пароль">
          <button>Войти</button>
        </div>
      </div>
      <img class="arrow-form" src="../../assets/img/arrow-form.png" alt="">
    </div>
    <div class="row">
      <div class="copyright">
        © 2000-2021 ООО «ИГД»
      </div>
      <div class="social-link">
        <a href="#" class="link-item">Facebook</a>
        <a href="#" class="link-item">Instagram</a>
        <a href="#" class="link-item">ВКонтакте</a>
      </div>
      <div></div>
    </div>
  </section>
</template>

<script>
export default {
  name: "Form"
}
</script>

<style scoped>
.form {
  background-color: #f5f5f6;
  display: grid;
}

.mt-170 {
  margin-top: 170px;
}

.arrow-form {
  position: absolute;
  bottom: -70px;
  right: 50%;
  left: 48%;
  transform: translate(-50%, -50%);
}

.form .row {
  position: relative;
  padding: 0 230px;
  display: flex;
  justify-content: space-between;
}
.copyright {
  font-size: 16px;
  line-height: 22px;
  color: #212327;
  font-weight: bold;
}
.social-link {
  display: flex;
}
.form > .row:last-child {
  padding: 0 285px;
  display: flex;
  justify-content: space-between;
  margin-bottom: 60px;
}
.form > .row:last-child > div {
  width: 33%;
  text-align: left;
}
.send-a-request {
  font-size: 44px;
  letter-spacing: 1px;
  line-height: 50px;
  color: #282828;
  margin-bottom: 44px;
  font-family: "G TEesti Pro Display";
  font-weight: bold;
}

.wrapper-form {
  display: grid;
  text-align: left;
  padding: 75px 100px;
}

label {
  margin-left: 40px;
  margin-bottom: 23px;
  font-size: 24px;
  line-height: 17px;
  color: #48802d;
  font-family: "G TEesti Pro Display";
  font-weight: 500
}

input {
  margin-bottom: 50px;
  border-radius: 37px;
  box-shadow: 0 0 59px rgb(44, 44, 44, 0, 05);
  background-color: #ffffff;
  border: 1px solid #c4c4c4;
  padding: 30px 40px;
  font-size: 22px;
  letter-spacing: 1px;
  color: #a6a6a6;
  font-family: "G TEesti Pro Display";
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

button {
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

.link-item {
  font-size: 22px;
  line-height: 22px;
  color: #212327;
  font-family: "G TEesti Pro Display";
  font-weight: bold;
  text-decoration: none;
  margin-left: 30px;
}

.item-specialist {
  display: flex;
}

.item-specialist + .item-specialist {
  margin-top: 42px;
}

.col-6 > .item-specialist:last-child {
  margin-bottom: 240px;
}

p {
  font-size: 30px;
  line-height: 40px;
  color: #53a862;
  font-family: "G TEesti Pro Display";
  font-weight: 500;
  max-width: 200px;
  text-align: left;
  margin-left: 50px;
}

.col-6:nth-child(2) {
  width: 591px;
  height: 666px;
  border-radius: 12px;
  background-color: #e1fccf;
  background-image: url(../../assets/img/background_form.png);
  background-repeat: no-repeat;
  -moz-background-size: 100%;
  -webkit-background-size: 100%;
  -o-background-size: 100%;
  background-size: 100%;
  z-index: 1;
}

img {
  z-index: 2;
}

@media only screen and (max-width: 425px) {
  .form {
    padding:15px;
    display: block;
  }
  .arrow-form {
    display: none;
  }
  .form .row {
    display: block;
    padding:0px;
  }
  .col-6:nth-child(2) {
    max-width: 100%;
  }
  .wrapper-form {
    padding: 35px 25px;
  }
  .form > .row:last-child {
    padding: 0;
    display: block;
    margin-bottom: 30px;
  }
  .form > .row:last-child > div {
    width: 100%;
  }
  .social-link {
    display: flex;
    justify-content: space-between;
  }
  .link-item {
    margin-left: 0;
  }
  .copyright {
    padding: 15px 0;
    margin-top: 30px;
  }
  input {
    width: 210px;
    margin-left: auto;
    margin-right: auto;
  }
  .send-a-request {
    text-align: center;
  }
  button {
    margin: auto;
  }
  .mt-170 {
    margin-top: 0;
  }
  .col-6 > .item-specialist:last-child {
    margin-bottom: 60px;
  }
}
</style>