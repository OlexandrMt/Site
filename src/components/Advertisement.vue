<template>
  <div class="conteiner">
    <div class="flex-item flex-1">
      <div class="aside">
        <div class="aside-title">ГІРЧИЦЯ ЗЕРНА<br />ЧОРНА</div>
        <div class="aside-price">Від 65 грн за кг</div>
        <button class="aside-btn btn draw-border">Замовити</button>
      </div>
    </div>
    <div class="flex-item flex-2">
      <div class="center">
        <div class="center-title center-m-1">СПЕЦІЇ ОПТОМ</div>
        <div class="center-decs">ОПТ від 25 кг</div>
        <div class="center-title center-m-2">СПЕЦІЇ В РОЗДРІБ</div>
        <div class="center-decs">РОЗДРІБ від 50 грам</div>
        <div class="separete-line"></div>
        <div class="center-green-title">ТОВ НАЗВА</div>
        <div class="center-bottom">
          ВЛАСНИЙ ІМПОРТ <br />
          ПОМОЛ СПЕЦІЙ <br />
          ВИРОБНИЦТВО СУМІШЕЙ
        </div>
      </div>
    </div>
    <div class="flex-item flex-3">
      <div class="aside">
        <div class="aside-title">ГІРЧИЦЯ ЗЕРНА<br />ЖОВТА</div>
        <div class="aside-price">Від 65 грн за кг</div>
        <button class="aside-btn">Замовити</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.conteiner {
  display: flex;
  flex-wrap: wrap;
}
.flex-item {
  flex-grow: 1;
  display: flex;
  justify-content: center;
  text-align: center;
}
.flex-1 {
  background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url(@/assets/img/advertisment/dark.png);
  background-size: cover;
}
.flex-2 {
  background-image: url(@/assets/img/advertisment/background.png);
  background-size: cover;
}
.flex-3 {
  background: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url(@/assets/img/advertisment/light.png);
  background-size: cover;
}
.aside {
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  width: 300px;
  color: #fff;
}
.aside-title {
  margin-top: 139px;
  font-weight: 700;
  font-size: 24px;
  line-height: 29px;
}
.aside-price {
  margin-top: 15px;
  font-weight: 700;
  font-size: 20px;
  line-height: 24px;
}
.aside-btn {
  background: rgba(0, 0, 0, 0);
  border: 3px solid white;
  margin: 32px 0px 90px 0px;
  width: 240px;
  font-weight: 700;
  font-size: 20px;
  line-height: 50px;
  color: #fff;
  cursor: pointer;
}
.aside-btn:hover {
    background-color: #fff;
    color: #333333;
    transition: .3s;
}
.center {
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  width: 300px;
  color: #333333;
}
.center-title {
  font-weight: 700;
  font-size: 32px;
  line-height: 150%;
}
.center-m-1 {
  margin-top: 52px;
}
.center-m-2 {
  margin-top: 32px;
}
.center-desc {
  font-weight: 600;
  font-size: 18px;
  line-height: 162%;
}
.separete-line {
  margin: 40px 0px 20px 16%;
  width: 68%;
  background-color: #3e6e00;
  height: 1px;
}
.center-green-title {
  font-weight: 700;
  font-size: 24px;
  line-height: 162%;
  color: #3e6e00;
  margin-bottom: 15px;
}
.center-bottom {
  font-weight: 400;
  font-size: 18px;
  line-height: 164.43%;
  margin-bottom: 40px;
}
</style>
