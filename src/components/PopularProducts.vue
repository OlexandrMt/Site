<template>
  <div class="title">
    <div class="wrapper">
      <div class="left">ПОПУЛЯРНІ ТОВАРИ</div>
      <div class="center"></div>
      <div class="right">
        <img
          class="back"
          src="@/assets/img/PopularProducts/Vector.svg"
          alt="vector"
        />
        <img
          class="next"
          src="@/assets/img/PopularProducts/Vector.svg"
          alt="vector"
        />
      </div>
    </div>
    <div class="line"></div>
  </div>
  <div class="content">
    <div class="conteiner">
      <div class="flex-item">
        <div class="card">
          <div class="top">
            <div class="tag">ПОПУЛЯРНЕ</div>
            <div class="icon">
              <img src="@/assets/img/PopularProducts/heart.svg" alt="heart" />
            </div>
          </div>
          <div class="bottom">
            <div class="card-title">Гірчиця зерна чорна</div>
            <div class="price">
              <div class="green-price">Від <strong>65</strong> грн за кг</div>
            </div>
            <button class="btn">Замовити</button>
          </div>
        </div>
      </div>
      <div class="flex-item">
        <div class="card">
          <div class="top">
            <div class="tag">ПОПУЛЯРНЕ</div>
            <div class="icon">
              <img src="@/assets/img/PopularProducts/heart.svg" alt="heart" />
            </div>
          </div>
          <div class="bottom">
            <div class="card-title">Гірчиця зерна чорна</div>
            <div class="price">
              <div class="red-price">Від <strong>55</strong> грн за кг</div>
              <div class="old-price">Від <strong>65</strong> грн за кг</div>
            </div>
            <button class="btn">Замовити</button>
          </div>
        </div>
      </div>
      <div class="flex-item">
        <div class="card">
          <div class="top">
            <div class="tag">ПОПУЛЯРНЕ</div>
            <div class="icon">
              <img src="@/assets/img/PopularProducts/heart.svg" alt="heart" />
            </div>
          </div>
          <div class="bottom">
            <div class="card-title">Гірчиця зерна чорна</div>
            <div class="price">
              <div class="red-price">Від <strong>55</strong> грн за кг</div>
              <div class="old-price">Від <strong>65</strong> грн за кг</div>
            </div>
            <button class="btn">Замовити</button>
          </div>
        </div>
      </div>
      <div class="flex-item">
        <div class="card">
          <div class="top">
            <div class="tag">ПОПУЛЯРНЕ</div>
            <div class="icon">
              <img src="@/assets/img/PopularProducts/heart.svg" alt="heart" />
            </div>
          </div>
          <div class="bottom">
            <div class="card-title">Гірчиця зерна чорна</div>
            <div class="price">
              <div class="red-price">Від <strong>55</strong> грн за кг</div>
              <div class="old-price">Від <strong>65</strong> грн за кг</div>
            </div>
            <button class="btn">Замовити</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PopularProducts",
};
</script>

<style scoped>
.title {
  background-color: #f5f5f5;
  padding: 80px 20px 80px 20px;
}
.wrapper {
  display: flex;
}
.left {
  padding: 0px 0px 0px 20px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 48px;
  line-height: 150%;
  text-transform: uppercase;
  color: #333333;
}
.center {
  flex-grow: 1;
}
.back {
  padding: 0px 28px 0px 28px;
  cursor: pointer;
}
.next {
  padding: 0px 28px 0px 0px;
  transform: rotate(180deg);
  cursor: pointer;
}
.line {
  border: 1px solid #3E6E00;
  height: 1px;
  width: 74%;
  float: right;
}
.content {
  padding: 0px 10px 40px 10px;
  background-color: #f5f5f5;
}
.conteiner {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 15px;
}
.flex-item {
  width: calc(25% - 20px);
  min-width: 237px;
  margin: 0px 0px 40px 0px;
  display: flex;
}
.top {
  background-image: url(@/assets/img/PopularProducts/Photo.png);
  background-size: cover;
  width: 237px;
  height: 157px;
  overflow: hidden;
}
.tag {
  position: relative;
  background-color: #fff;
  transform: rotate(-45deg);
  text-align: center;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 12px;
  line-height: 18px;
  top: 26px;
  left: -84px;
}
.icon {
  position: relative;
  float: right;
  background: rgba(255, 255, 255, 0.6);
  width: 24px;
  height: 24px;
  top: -3px;
  left: -15px;
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
}
.bottom {
  background-color: #fff;
  text-align: center;
}
.card-title {
  padding: 20px 0px 10px 0px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 18px;
  line-height: 22px;
  color: #333333;
}
.green-price {
  padding: 5px 0px 28px 0px;
  font-family: "Roboto", sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 14px;
  color: #3e6e00;
}
.red-price {
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 700;
  font-size: 14px;
  color: #f23030;
}
.old-price {
  padding: 5px 0px 11px 0px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  line-height: 15px;
  text-decoration-line: line-through;
  color: #585858;
}
strong {
  font-size: 20px;
}
.old-price strong {
  font-size: 16px;
  font-weight: 300;
}
.btn {
  background-color: #fff;
  margin: 0px 0px 24px 0px;
  padding: 4px 36px 4px 36px;
  border: 1px solid #585858;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 21px;
  cursor: pointer;
}
.btn:hover {
    background-color: #585858;
    color: #fff;
    transition: .3s;
}
@media screen and (max-width: 1012px) {
  .conteiner {
    justify-content: space-between;
  }
  .flex-item {
    width: calc(33.33% - 20px);
    display: flex;
    justify-content: center;
  }
}
@media screen and (max-width: 760px) {
  .wrapper {
    display: block;
  }
  .left {
    padding: 0;
    text-align: center;
  }
  .right {
    margin: 10px auto 20px auto;
    text-align: center;
  }
  .back {
    padding: 0px 28px 0px 0px;
  }
  .line {
    text-align: center;
    margin: 0px 13% 0px 0px;
  }
}
@media screen and (max-width: 760px) {
  .conteiner {
    justify-content: center;
  }
}
</style>
