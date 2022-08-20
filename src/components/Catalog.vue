<template>
  <div class="title">
    <div class="title-wrapper">
      <div class="left">
        <img src="@/assets/img/catalog/telephon.svg" alt="telephon" />
      </div>
      <div class="center">
        <div class="text">КАТАЛОГ</div>
        <div class="line"></div>
      </div>
      <div class="right">
        <img src="@/assets/img/catalog/telephon.svg" alt="telephon" />
      </div>
    </div>
  </div>
  <div class="conteiner">
    <div class="flex-item item-1">
      <div class="tag">СПЕЦІЇ</div>
    </div>
    <div class="flex-item item-2"><div class="tag">СУМІШІ СПЕЦІЙ</div></div>
    <div class="flex-item item-3"><div class="tag">ХАРЧОВІ ДОБАВКИ</div></div>
    <div class="flex-item item-4">
      <div class="tag">ГОРІХИ І СУХОФРУКТИ</div>
    </div>
    <div class="flex-item item-5"><div class="tag">КРУПИ</div></div>
    <div class="flex-item item-6">
      <div class="tag">НАБОРИ І ПОДАРУНКИ</div>
    </div>
    <div class="flex-item item-7">
      <div class="tag">КОНДИТЕРСЬКІ СКЛАДОВІ</div>
    </div>
    <div class="flex-item item-8"><div class="tag">АКСЕСУАРИ</div></div>
  </div>
  <div class="conteiner"></div>
</template>

<script>
export default {
  name: "Catalog",
};
</script>

<style scoped>
.title {
  padding: 80px 20px 74px 20px;
}
.title-wrapper {
  display: flex;
}
.left,
.right {
  width: 80px;
  height: 80px;
  background-color: #3e6e00;
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
}
.left {
  opacity: 0;
}
.center {
  flex-grow: 1;
}
.text {
  text-align: center;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 48px;
  line-height: 72px;
  letter-spacing: 0.06em;
  text-transform: uppercase;
  color: #363637;
}
.line {
  height: 1px;
  width: 85%;
  margin: auto;
  border: 1px solid #3E6E00;
}
.conteiner {
  display: flex;
  flex-wrap: wrap;
  width: 100%;
  padding: 0px 10px 80px 10px;
}
.flex-item {
  height: 230px;
  width: 231px;
  margin: 0px 10px 20px 10px;
  flex-grow: 1;
  background-size: cover;
}
.item-1 {
  background-image: url(@/assets/img/catalog/spices.png);
}
.item-2 {
  background-image: url(@/assets/img/catalog/mixture.png);
}
.item-3 {
  background-image: url(@/assets/img/catalog/supplements.png);
}
.item-4 {
  background-image: url(@/assets/img/catalog/nuts.png);
}
.item-5 {
  background-image: url(@/assets/img/catalog/cereals.png);
}
.item-6 {
  background-image: url(@/assets/img/catalog/gift.png);
}
.item-7 {
  background-image: url(@/assets/img/catalog/chocolate.png);
}
.item-8 {
  background-image: url(@/assets/img/catalog/cereals.png);
}
.tag {
  background-color: #fff;
  margin: 182px 0px 0px 0px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 17px;
  line-height: 28px;
  text-align: center;
  color: #333333;
}
@media screen and (max-width: 550px) {
  .left {
    display: none;
  }
}
@media screen and (max-width: 420px) {
  .right {
    display: none;
  }
}
</style>
