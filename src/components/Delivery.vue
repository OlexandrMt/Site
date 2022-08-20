<template>
  <div class="title">ДОСТАВКА</div>
  <div class="line">
    <div></div>
  </div>
  <div class="content">
    <div class="conteiner">
      <div class="left">
        <img src="@/assets/img/delivery/truck.png" alt="" />
      </div>
      <div class="decor"></div>
      <div class="right">
        <p>
          Ванілін міститься в рослині з однойменною назвою — ванілі, а також у
          картопляному лушпинні, тростинному цукрі, перуанському бальзамі,
          малині, оливковій олії та спирті-сирці. А у вівсянці та каві він
          з'являється після термообробки.
        </p>
        <br />
        <p>
          Ванілін міститься в рослині з однойменною назвою — ванілі, а також у
          картопляному лушпинні, тростинному цукрі, перуанському бальзамі,
          малині, оливковій олії ...
        </p>
        <button>
          Детальніше 
          <img class="arroy" src="@/assets/img/delivery/arrow_left.svg" alt="" />
        </button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Delivery",
};
</script>

<style scoped>
.title {
  background-color: #edecec;
  padding: 80px 40px 24px 0px;
  text-align: end;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 48px;
  line-height: 150%;
  color: #363637;
}
.line {
  background-color: #edecec;
}
.line div {
  border-bottom: 1px solid #3e6e00;
  width: 74%;
}
.content {
  padding: 72px 0px 64px 0px;
  background-color: #edecec;
}
.conteiner {
  display: flex;
}
.decor {
  background-color: #fcffe2;
  margin-top: 24px;
  width: 15px;
  height: 462px;
  flex-shrink: 0;
}
.right {
  padding: 32px 40px 0px 20px;
}
p {
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;
  /* or 27px */
  color: #3e3f46;
}
button {
  margin-top: 84px;
  padding: 12px 16px 12px 16px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 20px;
  color: #333333;
  border: 1px solid #333333;
}
.arroy {
    margin-left: 62px;
    position: relative;
    top: 2px;
}
button:hover {
    border: 1px solid #333333;
    box-shadow: 5px 3px 3px black;
    cursor: pointer;
    transition: .3s;
}
@media screen and (max-width: 826px) {
  button {
    margin-top: 30px;
  }
}
@media screen and (max-width: 798px) {
  .left, .decor {
    display: none;
  }
  .right {
    padding: 32px 40px 0px 40px;
  }
}
@media screen and (max-width: 540px) {
  .title {
    text-align: center;
    padding: 80px 0px 24px 0px;
  }
}
</style>
