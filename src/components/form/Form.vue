<template>
  <section class="form">
    <div class="row">
      <div class="col-6 mt-170">
        <div class="item-specialist">
          <img src="img/15.png" alt="" />
          <p>Свободных специалистов</p>
        </div>
        <div class="item-specialist">
          <img src="img/15.png" alt="" />
          <p>Свободных специалистов</p>
        </div>
        <div class="item-specialist">
          <img src="img/15.png" alt="" />
          <p>Свободных специалистов</p>
        </div>
      </div>
      <div class="col-6">
        <div class="wrapper-form">
          <div class="send-a-request">Отправить запрос</div>
          <label for="login">Ваше имя:</label>
          <input id="login" type="text" placeholder="Имя" />
          <label for="password">Телефон:</label>
          <input id="password" type="text" placeholder="Телефон" />
          <button>Войти</button>
        </div>
      </div>
      <img class="arrow-form" src="img/arrow-form.png" alt="" />
    </div>
    <img class="arrow-form-mobile" src="img/arrow-form.png" alt="" />
    <div class="row">
      <div class="copyright">© 2000-2021 ООО «ИГД»</div>
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
  name: "Form",
};
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
.arrow-form-mobile {
  width: 100%;
  display: none;
}

.form .row {
  position: relative;
  padding: 0 230px;
  display: flex;
  justify-content: space-between;
}
.copyright {
  font-family: "GT Eesti Pro Display", serif;
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
  font-family: "GT Eesti Pro Display", serif;
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
  font-family: "GT Eesti Pro Display", serif;
  font-weight: 500;
}

input {
  margin-bottom: 50px;
  border-radius: 37px;
  box-shadow: 0 0 59px rgb(44, 44, 44, 0, 05);
  background-color: #ffffff;
  border: 1px solid #c4c4c4;
  padding: 30px 40px;
  font-size: 15px;
  letter-spacing: 1px;
  color: #a6a6a6;
  font-family: "GT Eesti Pro Display", serif;
}

button:not(:disabled) {
  cursor: pointer;
}
button:hover {
  background-image: none;
  background-color: #ffffff;
  border: 2px solid #6aaf5c;
  color: #6aaf5c !important;
  transition: 0.3s;
}

button {
  width: 268px;
  height: 75px;
  box-shadow: 6px 5px 20px rgb(82, 151, 34, 0.21);
  border-radius: 38px;
  background-color: #fff;
  background-image: linear-gradient(0deg, #6aaf5c 0, #52b709),
    linear-gradient(
      36deg,
      hsla(0, 0%, 100%, 0),
      hsla(0, 0%, 100%, 0.16) 47%,
      hsla(0, 0%, 100%, 0.17) 50%,
      hsla(0, 0%, 100%, 0)
    );
  color: #fff;
  font-family: "Muller", serif;
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
  font-family: "GT Eesti Pro Display", serif;
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
.item-specialist img {
  width: 70px;
  height: 84px;
  margin: auto;
}
p {
  font-size: 30px;
  line-height: 40px;
  color: #53a862;
  font-family: "GT Eesti Pro Display", serif;
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
  background-image: url(/img/background_form.png);
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

@media only screen and (max-width: 360px) {
  .social-link {
    display: flex;
    text-align: left !important;
    width: 100%;
    flex-direction: unset;
  }
  .social-link a {
    font-size: 15px;
    text-align: left;
  }
  .copyright {
    font-size: 13px;
  }
  .link-item {
    width: 100%;
    padding: 5px 0;
  }
  p {
    margin-left: 30px;
  }
  input#login,
  input#password {
    width: 205px;
    font-size: 15px;
    letter-spacing: 0.32px;
  }

  .wrapper-form button {
    width: 200px;
    height: 60px;
  }
}

@media only screen and (max-width: 768px) {
  .form {
    padding: 15px;
    padding-top: 0;
    display: block;
  }
  .arrow-form {
    display: none;
  }
  .form .row {
    padding: 0;
    display: flex;
    flex-direction: column-reverse;
  }
  .col-6:nth-child(2) {
    max-width: 100%;
    width: 530px;
    margin: auto;
    height: 460px;
  }
  .wrapper-form {
    padding: 45px 10px;
  }
  .arrow-form-mobile {
    display: block;
    width: 400px;
    margin: auto;
  }
  label {
    font-size: 15px;
    font-weight: 500;
    font-style: normal;
    letter-spacing: normal;
    line-height: 16.81px;
    text-align: center;
    margin-left: 0;
    margin-bottom: 15px;
  }
  .mt-170 {
    margin-top: 90px;
  }
  .form > .row:last-child {
    margin-top: 90px;
    padding: 0;
    display: block;
    margin-bottom: 30px;
    display: flex;
    flex-direction: column-reverse;
  }
  .form > .row:last-child > div {
    width: 100%;
    text-align: center !important;
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
    padding: 20px 25px;
  }
  .send-a-request {
    text-align: center;
    display: none;
  }
  button {
    margin: auto;
    font-size: 15px;
    font-weight: 400;
    letter-spacing: 1.1px;
    line-height: 47.92px;
  }
  .item-specialist + .item-specialist {
    margin-top: 0;
  }
  .item-specialist {
    margin: 15px;
    justify-content: center;
    font-size: 25px;
  }
  .item-specialist img {
    width: 54px;
    height: 64px;
    margin: auto 0;
  }
  .social-link {
    justify-content: space-around;
  }
  .col-6 > .item-specialist:last-child {
    margin-bottom: 60px;
  }
}
@media only screen and (max-width: 425px) {
  .arrow-form-mobile {
    width: 100%;
  }
  .social-link {
    justify-content: space-between;
  }
}
</style>