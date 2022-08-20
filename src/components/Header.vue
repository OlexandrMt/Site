<template>
  <header class="header">
    <div class="conteiner">
      <div class="logo">LOGO</div>
      <div class="input">
        <input type="text" placeholder="Пошук по сайту" />
        <div class="lens">
          <img src="@/assets/img/header/search.svg" alt="" srcset="">
        </div>
      </div>
      <div class="telephon">
        <div class="number">0 (800) 755 855</div>
        <div class="separete"></div>
        <div class="description">Безкоштовно з усіх номерів України</div>
      </div>
      <div class="enter">
        <div>
          <img src="@/assets/img/header/Oval.svg" alt="head" />
          <img src="@/assets/img/header/Shape.svg" alt="head" />
        </div>
        <div>ВХІД</div>
      </div>
      <div class="ua">UA</div>
      <img src="@/assets/img/header/Vector.svg" alt="\/" />
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header {
  width: 100%;
  background-color: #fff;
  padding: 25px 40px 24px 40px;
}
.conteiner {
  display: flex;
}
.logo {
  background-color: #fff;
  width: 90px;
  text-decoration: none;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 30px;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  font-variant: small-caps;
}
.input {
  background-color: #fff;
  padding-left: 20px;
  padding-right: 10px;
  height: 30px;
  align-self: flex-end;
  flex-grow: 1;
  display: flex;
}
.input input {
  border-radius: 0px;
  height: 30px;
  width: 100%;
  border: 0px;
  background-color: #f5f5f5;
  padding-inline: 10px;
}
.input .lens {
  position: relative;
  float: right;
  border-radius: 0px;
  border: 0px;
  background-color: #f5f5f5;
  line-height: 26px;
  margin: 2px 0px 2px 0px;
  right: 28px;
}
.telephon {
  display: flex;
  padding-left: 26px;
  padding-right: 30px;
  background-color: #fff;
}
.number {
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 30px;
  color: #585858;
}
.separete {
  margin-left: 10px;
  margin-right: 10px;
  width: 1px;
  height: 100%;
  background-color: #c4c4c4;
}
.description {
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 12px;
  color: #585858;
  max-width: 130px;
}
.enter {
  background-color: #fff;
  padding-inline: 10px;
  display: flex;
  line-height: 30px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 400;
  font-size: 13px;
  color: #585858;
  cursor: pointer;
  margin-right: 20px;
}
.enter:hover {
  background-color: #f5f5f5;
  border-radius: 5px;
  box-shadow: 5px 3px 3px #585858;
}
.enter img {
  display: block;
}
img:first-child {
  padding-top: 5px;
  padding-left: 4px;
  padding-right: 10px;
}
.ua {
  background-color: #fff;
  text-decoration: underline;
  font-family: "Fira Sans", sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 30px;
  color: #585858;
  align-self: flex-end;
}
@media screen and (max-width: 880px) {
  .telephon {
    padding-left: 0px;
    padding-right: 10px;
  }
  .separete {
    display: none;
  }
  .description {
    display: none;
  }
}
@media screen and (max-width: 690px) {
  .header {
    padding: 15px 10px 14px 10px;
  }
  .logo {
    width: 60px;
  }
  .telephon {
    display: none;
  }
  .enter {
    margin-right: 0px;
  }
}
@media screen and (max-width: 400px) {
  .lens {
    display: none;
  }
}
</style>
