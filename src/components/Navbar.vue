<template>
  <nav class="navbar">
    <div class="conteiner">
      <div class="catalog">
        <div>КАТАЛОГ</div>
        <img src="@/assets/img/header/Vector.svg" alt="vector" />
      </div>
      <div class="menu">
        <div class="menu-item">ПОСЛУГИ</div>
        <div class="menu-item">ДОСТАВКА</div>
        <div class="menu-item">ОПЛАТА</div>
        <div class="menu-item">ДОКУМЕНТИ</div>
        <div class="menu-item">НОВИНИ</div>
        <div class="menu-item">СТАТТІ</div>
        <div class="menu-item">СПІВПРАЦЯ</div>
        <div class="menu-item">ПРО КОМПАНІЮ</div>
        <div class="menu-item">КОНТАКТИ</div>
        <div class="menu-btn">
          <label for="check-menu">МЕНЮ</label>
          <img src="@/assets/img/header/Vector.svg" alt="vector" />
        </div>
      </div>
      <div class="icons">
        <img src="@/assets/img/navbar/heart.svg" alt="heart" />
        <img class="cart" src="@/assets/img/navbar/cart.svg" alt="cart" />
        <div class="number">5</div>
      </div>
    </div>
  </nav>
  <input type="checkbox" id="check-menu" />
  <div class="drop">
    <div class="drop-menu">ПОСЛУГИ</div>
    <div class="drop-menu">ДОСТАВКА</div>
    <div class="drop-menu">ОПЛАТА</div>
    <div class="drop-menu">ДОКУМЕНТИ</div>
    <div class="drop-menu">НОВИНИ</div>
    <div class="drop-menu">СТАТТІ</div>
    <div class="drop-menu">СПІВПРАЦЯ</div>
    <div class="drop-menu">ПРО КОМПАНІЮ</div>
    <div class="drop-menu">КОНТАКТИ</div>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style scoped>
.navbar {
  background-color: #f5f5f5;
  width: 100%;
  padding: 20px 40px 20px 40px;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 12px;
  line-height: 152.25%;
  letter-spacing: 0.03em;
  text-transform: uppercase;
  font-variant: small-caps;
  color: #333333;
}
.conteiner {
  display: flex;
  text-align: center;
  align-items: center;
}
.catalog {
  display: flex;
  cursor: pointer;
}
.catalog img {
  margin: 0px 0px 0px 4px;
}
#check-menu {
  display: none;
}
.menu {
  flex-grow: 1;
  display: flex;
  justify-content: space-between;
}
.menu-item {
  flex-grow: 1;
  cursor: pointer;
}
.menu-btn {
  display: none;
}
.icons {
  display: flex;
  cursor: pointer;
}
.cart {
  margin: 0px 0px 0px 20px;
}
.number {
  background-color: teal;
  position: relative;
  align-self: flex-start;
  width: 18px;
  border-radius: 50%;
  color: #fff;
  top: -6px;
  left: -8px;
}
.drop {
  display: none;
  font-family: "Proxima Nova", sans-serif;
  font-style: normal;
  font-weight: 600;
  font-size: 12px;
  color: #333333;
}
@media screen and (max-width: 910px) {
  .menu-item {
    display: none;
  }
  .menu {
    justify-content: center;
  }
  .menu-btn {
    display: flex;
    cursor: pointer;
  }
  .menu-btn img {
    margin: 0px 0px 0px 4px;
  }
  .drop {
    display: block;
    transform: translateY();
    max-height: 0px;
    overflow: hidden;
    transition: 0.8s all;
  }
  .drop-menu {
    background-color: #f5f5f5;
    border-top: 1px solid #fff;
    padding: 2px 0px 2px 20px;
    cursor: pointer;
  }
  #check-menu:checked ~ .drop {
    max-height: 252px;
  }
}
@media screen and (max-width: 600px) {
  .navbar {
    padding: 20px 20px 20px 40px;
  }
}
</style>
