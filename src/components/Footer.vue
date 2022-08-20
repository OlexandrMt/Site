<template>
  <footer>
    <div class="top">
      <div class="wrapper">
        <div class="wrapper-left">
          <div class="menu">Послуги</div>
          <div class="menu">Доставка</div>
          <div class="menu">Оплата</div>
          <div class="menu">Документи</div>
          <div class="menu">Новини</div>
          <div class="menu">Статті</div>
          <div class="menu">Співпраця</div>
          <div class="menu">Про компанію</div>
          <div class="menu">Спеції</div>
          <div class="menu">Суміш спецій</div>
          <div class="menu">Харчові добавки</div>
          <div class="menu">Кондитерські складові</div>
          <div class="menu">Горіхи і сухофрукти</div>
          <div class="menu">Крупи</div>
          <div class="menu">Набори і подарунки</div>
          <div class="menu">Аксесуари</div>
          <div class="menu">Новинки</div>
          <div class="menu">Знижки</div>
          <div class="menu">Популярне</div>
        </div>
        <div class="wrapper-right">
          <div class="logo">LOGO</div>
          <div class="telephon">+38 097 710 20 06<br />0 (800) 755 855</div>
          <div class="email">info.mailbox90@gmail.com</div>
          <div class="icons">
            <img src="@/assets/img/footer/facebook.svg" alt="facebook" />
            <img src="@/assets/img/footer/youtube.svg" alt="youtube" />
            <img src="@/assets/img/footer/twitter.svg" alt="twitter" />
            <img src="@/assets/img/footer/viber.svg" alt="viber" />
            <img src="@/assets/img/footer/telegram.svg" alt="telegram" />
          </div>
        </div>
      </div>
    </div>
    <div class="line"></div>
    <div class="center">
      <div class="conteiner">
        <div class="conteiner-left">
          <div class="conteiner-title">ПІДПИСАТИСЬ НА РОЗСИЛКУ</div>
          <input type="text" placeholder="Введіть свій email" />
          <button>ПІДПИСАТИСЬ</button>
          <div class="ask">
            <div>У вас залишились питання?</div>
            <button>НАПИСАТИ ЛИСТ</button>
          </div>
        </div>
        <div class="conteiner-right">
          Як користуватись сайтом?<br />Питанняі відповіді
        </div>
      </div>
    </div>
    <div class="line"></div>
    <div class="bottom">© ТОВ "НАЗВА" 2013</div>
  </footer>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
footer {
  background-color: #edecec;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  color: #333333;
}
.wrapper {
  padding: 48px 80px 48px 80px;
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.wrapper-left {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  height: 200px;
}
.menu {
  font-weight: 400;
  font-size: 14px;
  line-height: 21px;
  margin: 0px 90px 4px 0px;
}
.menu:hover {
  cursor: pointer;
  color: #000;
  text-decoration: underline;
}
.wrapper-right {
  text-align: center;
}
.logo {
  font-weight: 600;
  font-size: 24px;
  line-height: 152.25%;
  /* identical to box height, or 37px */
  letter-spacing: 0.03em;
  text-transform: uppercase;
  font-variant: small-caps;
  color: #000000;
  margin-bottom: 40px;
}
.telephon {
  font-weight: 600;
  font-size: 20px;
  line-height: 152.25%;
  /* or 30px */
}
.email {
  font-weight: 400;
  font-size: 18px;
  line-height: 152.25%;
  /* or 27px */
  margin: 20px 0px 28px 0px;
}
.icons img {
  margin: 0px 9px 0px 9px;
  cursor: pointer;
}
.conteiner {
  padding: 48px 80px 48px 80px;
  display: flex;
  gap: 103px;
  flex-wrap: wrap;
}
.conteiner-title {
  font-weight: 700;
  font-size: 16px;
  line-height: 24px;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  margin-bottom: 32px;
}
input {
  background-color: #ededed;
  border: 0px;
  border-bottom: 1px solid #3e3f46;
  width: 231px;
  height: 30px;
  padding-left: 5px;
}
button {
  margin-left: 20px;
  padding: 7px 9px 7px 9px;
  border-radius: 0;
  border: 1px solid #333333;
  font-weight: 500;
  font-size: 10px;
  line-height: 14px;
}
button:hover {
  border: 1px solid #333333;
  box-shadow: 5px 3px 3px black;
  cursor: pointer;
  transition: 0.3s;
}
.ask {
  margin-top: 48px;
  font-weight: 400;
  font-size: 13px;
}
.ask div {
  display: inline;
  margin-right: 20px;
  line-height: 30px;
}
.conteiner-right {
  display: flex;
  align-items: center;
  font-weight: 400;
  font-size: 13px;
  line-height: 24px;
}
.conteiner-right:hover {
    text-decoration: underline;
    cursor: pointer;
}
.line {
  background-color: #000;
  height: 1px;
  width: 96%;
  margin: auto;
}
.bottom {
  padding: 20px 0px 7px 0px;
  font-weight: 400;
  font-size: 14px;
  line-height: 162%;
  /* identical to box height, or 23px */
  letter-spacing: 0.05em;
  text-align: center;
  text-transform: uppercase;
  color: #3e3f46;
}
@media screen and (max-width: 920px) {
  .wrapper-left {
    height: 250px;
  }
}
@media screen and (max-width: 764px) {
  .conteiner {
    justify-content: center;
  }
}
@media screen and (max-width: 740px) {
  .wrapper {
    display: block;
  }
  .wrapper-left {
    text-align: center;
    height: 250px;
  }
  .menu {
    margin-right: 0px;
  }
  .logo {
    margin-top: 20px;
  }
}
@media screen and (max-width: 502px) {
  .wrapper {
    padding: 48px 10px 48px 10px;
  }
  .conteiner {
    padding: 48px 10px 48px 10px;
  }
}
@media screen and (max-width: 400px) {
  .conteiner {
    text-align: center;
  }
  button {
    margin-top: 20px;
  }
}

</style>
