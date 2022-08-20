<template>
  <div class="title">
    НАШІ ПЕРЕВАГИ
    <div class="line"></div>
  </div>
  <div class="content">
    <div class="conteiner">
      <div class="flex-box">
        <div class="truck">
          <img src="@/assets/img/advantages/truck.svg" alt="" />
        </div>
        <div class="text">ВІДПРАВКА В ДЕНЬ ЗАМОВЛЕННЯ</div>
      </div>
      <div class="flex-box">
        <div class="medal">
          <img src="@/assets/img/advantages/medal.svg" alt="" />
        </div>
        <div class="text">СТАБІЛЬНО ВИСОКА ЯКІСТЬ</div>
      </div>
      <div class="flex-box">
        <div class="box">
          <img src="@/assets/img/advantages/box.svg" alt="" />
        </div>
        <div class="text">ІНДИВІДУАЛЬНА УПАКОВКА</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Advantages",
};
</script>

<style scoped>
.title {
  padding: 80px 0px 0px 0px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 48px;
  line-height: 150%;
  text-align: center;
  text-transform: uppercase;
  color: #333333;
}
.line {
  margin: 24px auto 100px auto;
  height: 1px;
  width: 80%;
  border-bottom: 1px solid #3e6e00;
}
.content {
  padding: 0px 20px 60px 20px;
}
.conteiner {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
}
.flex-box {
  width: 315px;
  text-align: center;
  margin-bottom: 20px;
}
.truck {
    margin-bottom: 50px;
}
.medal {
    margin-bottom: 38px;
}
.box {
    margin-bottom: 34px;
}
.text {
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 22px;
  line-height: 150%;
  /* or 33px */
  letter-spacing: 0.08em;
  color: #333333;
}
@media screen and (max-width: 984px) {
  .conteiner {
    justify-content: center;
  }
}
@media screen and (max-width: 410px) {
  .title {
    font-size: 36px;
  }
}
</style>
