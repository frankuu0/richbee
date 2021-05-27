<template>
  <div id="popup" class="hidden">
    <div id="form">
      <div class="titleP"><h2>Вход в личный кабинет</h2><button @click="hide" style="font-size:36px">X</button></div>
    <span>Email</span>
    <input type="email" placeholder="Email">
    <span>Пароль</span>
    <input type="password" placeholder="Пароль">
    <span id="forget" style="text-decoration:underline">Забыли пароль?</span>
    <div class="btnP">
      <button class="yellow">Войти</button><button class="light">Зарегистрироваться</button>
    </div>
    </div>
    
  </div>
  <div id="headContainer">
    <div id="header">
      <ul>
        <li>Оптовикам</li>
        <li>Заказ и доставка</li>
        <li>О компании</li>
        <li>Обзоры</li>
        <li>Контакты</li>
      </ul>
      <ul>
        <li
          style="font-weight: bold; color:#FFD637; border-bottom: 2px solid #FFD637; border-bottom-style: dashed;"
        >
          Заказть звонок
        </li>
        <li><img src="../src/assets/vk.png" alt="vk" /></li>
        <li><img src="../src/assets/wa.png" alt="whatsapp" /></li>
        <li><img src="../src/assets/inst.png" alt="instagram" /></li>
        <li style="font-weight: bold; color:white;">info@richbee.ru</li>
        <hr />
        <li style="font-weight: bold; color:white;">8(800)541-13-35</li>
      </ul>
    </div>
    <div id="search">
      <div id="logo">
        <img src="../src/assets/Rlogo.png" alt="logo" />
        <img src="../src/assets/Rtext.png" alt="logo" />
      </div>
      <div id="searchBar">
        <input type="text" placeholder="Поиск товаров по сайту" />
        <button><img src="../src/assets/magnifier.png" alt="search" /></button>
      </div>
      <div>
        <button class="headBtn"  @click="show">
          <img src="../src/assets/people.png" alt="people" />
          <hr />
          <div style="text-align:left">
            <span style="color: #383838">Вход</span><br /><span
              style="color: #ACACAC"
              >Регистрация</span
            >
          </div>
        </button>
      </div>
      <div>
        <button class="headBtn">
          <img src="../src/assets/cart.png" alt="people" />
          <hr />
          <div style="text-align:left">
            <span style="color: #383838">4 127 350 ₽</span><br /><span
              style="color: #ACACAC"
              >3 534 товаров</span
            >
          </div>
        </button>
      </div>
    </div>
    <div id="menu">
      <ul>
        <li class="dark">Каталог товаров</li>
        <li class="dark">Акции и скидки</li>
        <hr />
        <li>Автосвет</li>
        <li>Автохимия</li>
        <li>Инструменты</li>
        <li>Крепеж</li>
        <li>Электрика</li>
        <li>Посуда</li>
        <li>Аксессуары</li>
        <li>Брызговики</li>
        <li>Фары</li>
      </ul>
    </div>
  </div>
  <p style="margin: 40px 120px; color:#8f8f8f; font-size: 14px">
    Главная / Каталог / Инструменты /
    <span style="color:#383838"
      >Набор инструментов МАСТАК 94 предмета 01-094C [01-094C]</span
    >
  </p>
  <h2
    style="font-weight: 500;font-size: 24px;line-height: 28px;color: #0B0B0B;"
  >
    Набор инструментов МАСТАК 94 предмета 01-094C [01-094C]
  </h2>
  <div id="slider">
    <div id="sliderBtn">
      <button id="up" @click="back">
        <img src="../src/assets/up.png" alt="up" />
      </button>
      <div class="smallasset">
        <div><img src="../src/assets/1.png" alt="1" /></div>
        <div><img src="../src/assets/2.png" alt="2" /></div>
        <div><img src="../src/assets/3.png" alt="3" /></div>
        <div><img src="../src/assets/4.png" alt="4" /></div>
      </div>
      <button id="down" @click="next">
        <img src="../src/assets/down.png" alt="down" />
      </button>
    </div>
    <div id="sliderContent">
      <div id="sliderImages">
        <div><img src="../src/assets/1.png" alt="1" /></div>
        <div><img src="../src/assets/2.png" alt="2" /></div>
        <div><img src="../src/assets/3.png" alt="3" /></div>
        <div><img src="../src/assets/4.png" alt="4" /></div>
      </div>
    </div>
    <div id="about">
      <p style="color:#797979; font-size:14px">
        Внутрениий код товара:
        <span style="color:#383838; font-weight:700">21215</span>
      </p>
      <p style="color:#797979; font-size:14px">
        Артикул: <span style="color:#383838; font-weight:700">01-093C</span>
      </p>
      <p class="aboutGray">
        Цена указана за набор инструментов из 94-х предметов
      </p>
      <div id="aboutPrice">
        <div style="color: #383838;">
          <span style="font-weight: bold;font-size: 32px;line-height: 37px;"
            >6 640 ₽</span
          ><span style="font-size:14px">ваша цена</span>
        </div>
        <div style="color: #949494;">
          <span style="font-weight: bold;font-size: 20px;line-height: 23px;"
            >5 350 ₽ <span id="iBig" class="infoafter">i</span></span
          ><span style="font-size:14px">опт</span>
        </div>
      </div>
      <button class="yellow big">
        в корзину
      </button>
      <img src="../src/assets/green.png" alt="green" />
      <span class="aboutSpan">На центральном складе</span>
      <span class="aboutSpan">В 2-х наших магазинах</span>
    </div>
  </div>

  <div id="nav">
    <router-link to="/">О товаре</router-link>
    <router-link to="/about">Наличие товара</router-link>
  </div>
  <router-view id="router" />

  <h2 style="font-weight: bold;font-size: 36px;line-height: 42px;color: #0B0B0B;">
    Аналоги
  </h2>
  <div id="cards">
    <div class="card">
      <img src="../src/assets/card1.png" alt="" />
      <span class="cardName">Набор инструментов МАСТАК 94 предмета 01-094C [01-094C]</span>
      <span style="font-size:12px;color:#32a73c;">В наличии</span>
      <span style="font-weight: 900;font-size: 24px;line-height: 28px;color: #383838;">1 150 ₽</span>
      <div><span class="redS">708 ₽ (оптовая)</span><img src="../src/assets/info1.png" alt="" class="infoafter"></div>
      <button class="yellow">В корзину</button>
    </div>
    <div class="card">
      <img src="../src/assets/card2.png" alt="" />
      <span class="cardName">Маяк импульсный светодиодный на магните 10-30V 2-режима</span>
      <span style="font-size:12px;color:#32a73c;">В наличии</span>
      <span style="font-weight: 900;font-size: 24px;line-height: 28px;color: #383838;">1 150 ₽</span>
      <div><span class="redS">708 ₽ (оптовая)</span><img src="../src/assets/info1.png" alt="" class="infoafter"></div>
      <button class="yellow">В корзину</button>
    </div>
    <div class="card">
      <img src="../src/assets/card3.png" alt="" />
      <span class="cardName">Указатель габаритов с повторителем поворота «Бегущие огни» на
        светодиодах</span>
      <span style="font-size:12px;">Нет в наличии</span>
      <span style="font-weight: 900;font-size: 24px;line-height: 28px;color: #383838;">1 150 ₽</span>
      <div><span class="redS">708 ₽ (оптовая)</span><img src="../src/assets/info1.png" alt="" class="infoafter"></div>
      <button class="light">Сообщить о появлении</button>
    </div>
    <div class="card">
      <button class="sale">%</button>
      <img src="../src/assets/card4.png" alt="" />
      <span class="cardName">Фара противотуманная дальнего света круглая с желтым габаритом
        (двухрежимная) 12-24 В, 27 Вт, 4 узкая</span>
      <span style="font-size:12px;color:#32a73c;">В наличии</span>
      <span style="font-weight: 900;font-size: 24px;line-height: 28px;color: #383838;">1 150 ₽</span>
      <div><span class="redS">708 ₽ (оптовая)</span><img src="../src/assets/info1.png" alt="" class="infoafter"></div>
      <button class="yellow">В корзину</button>
    </div>
  </div>

  <div id="footer">
    <img src="../src/assets/invitation.png" alt="" />
    <h2 style="font-size:31px;margin:0;padding:50px">Будьте в курсе <br>новостей и акции</h2>
    <span style="font-size:16px">Подпишись на рассылку<br />и получайте первым информацию<br />об акциях
      Richbee</span>
    <input type="text" placeholder="Электронная почта"/>
    <button>Подписаться</button>
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap");

* {
  font-family: "Roboto", sans-serif;
  box-sizing: border-box;
}

.infoafter {
  display: block;
  position: relative;
  &::after {
    white-space: pre;
    content: 'Для получения оптовых\0aцен, добавьте в корзину\0aтоваров ещё на 10 000 руб\0a(по оптовым ценам)';
    position: absolute;
    top: 70px;
    left: 50%;
    z-index: -1;
    transform: translateX(-50%);
    width: max-content;
    opacity: 0;
    font-size: 13px;
    box-sizing: border-box;
    padding: 5px 10px;
    border-radius: 10px;
    background-color: rgba($color: #000000, $alpha: .7);
    color: white;
    transition: .3s;
  }
  &:hover::after {
      opacity: 1;
      top: 30px;
      z-index: 1;
  }
}

.redS {
  font-size: 14px;
line-height: 16px;

color: #F71412;
}

.light {
  text-transform: uppercase;
  font-size: 14px;
  background-color: #f8f8f8;
  color: #383838;
  border: 0;
  font-weight: bold;
  transition: 0.3s;
  cursor: pointer;
  &:hover {
    background-color: #efefef;
  }
}

#app {
  margin: 0 auto;
  width: 1440px;
  color: #2c3e50;
  background-color: #fff;
}

#headContainer {
  box-shadow: 0px 13px 22px rgba(228, 228, 228, 0.25);
}

#header {
  padding: 0 120px;
  background-color: #383838;
  color: #b8b8b8;
  height: 45px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  font-weight: normal;
  font-size: 14px;
  line-height: 16px;
  ul {
    padding: 0;
    width: 40%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    list-style-type: none;
    hr {
      margin: 0;
      height: 20px;
      width: 2px;
      background-color: #b8b8b8;
      border: 0;
    }
    li {
      cursor: pointer;
    }
  }
}

#slider,
#cards,
#footer,
h2,
#router {
  padding: 0 120px;
}

#router {
  transition: all 0.3s;
}

.hidden {
  display: none;
}

.show {
  z-index: 40;
  background-color: rgba(0,0,0,.7);
  position: fixed;
  top: 0;
  left: 0;
  width: 100vw;
  height: 100vh;
  #form {
    width: 600px;
    height: 514px;
    background-color: #fff;
    position: absolute;
    padding: 50px;
    top: 50%;
    left: 50%;
    transform: translate(-50%,-50%);
    display: flex;
    flex-direction: column;
    border-radius: 4px;
    input {
      margin: 5px 0 20px 0;
      width: 510px;
      height: 50px;
      background-color: #f8f8f8;
      padding: 20px;
      border: 1px solid #b8b8b8;
      border-radius: 4px;
      font-size: 16px;
    }
    .btnP {
      margin-top: 50px;
      display: flex;
      justify-content: space-between;
      button {
        width: 245px;
        height: 45px;
        border-radius: 4px;
      }
    }
    .titleP {
      display: flex;
      justify-content: space-between;
      margin-bottom: 30px;
      h2{
        text-align: left;
        font-size: 36px;
        margin: 0;
        padding: 0 20px 0 0;
        colors: #0b0b0b
      }
      button{
        background-color: #fff;
        border: 0;
        font-size: 16px;
        color:#b8b8b8;
        cursor: pointer;
      }
    }
  }
}

#search {
  padding: 35px 120px 40px 120px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  .headBtn {
    padding: 10px;
    display: flex;
    align-items: center;
    width: 180px;
    height: 48px;
    background-color: #f4f4f4;
    border: 0;
    border-radius: 4px;
    font-size: 13px;
    transition: 0.3s;
    cursor: pointer;
    img {
      width: 27px;
      height: 27px;
    }
    hr {
      margin: 0 5px;
      height: 42px;
      width: 2px;
      background-color: #e4e4e4;
      border: 0;
    }
    &:hover {
      background-color: #efefef;
    }
  }
  #searchBar {
    display: flex;
    align-items: center;
    input {
      padding: 0 20px;
      width: 540px;
      height: 48px;
      font-size: 14px;
      border: 1px solid #ecedef;
      border-radius: 4px 0 0 4px;
    }
    button {
      width: 48px;
      height: 48px;
      border-radius: 0 4px 4px 0;
      background: #ffd637;
      border: 0;
      cursor: pointer;
    }
  }
}

#menu {
  ul {
    margin: 0;
    padding: 0 120px 30px 120px;
    display: flex;
    align-items: center;
    justify-content: space-between;
    list-style-type: none;
    text-transform: uppercase;
    font-size: 14px;
    hr {
      height: 20px;
      width: 2px;
      margin: 0;
      background-color: #b8b8b8;
      border: 0;
    }
    li {
      color: #b8b8b8;
      cursor: pointer;
    }
    .dark {
      color: #383838;
      font-weight: 700;
    }
  }
}

#logo {
  display: flex;
  align-items: center;
  img {
    margin: 5px;
  }
}

#nav {
  margin: 20px 120px;
  padding: 10px 0;
  border-bottom: 1px solid #dfdfdf;

  a {
    font-weight: bold;
    color: #2c3e50;
    text-decoration: none;
    margin: 20px;
    padding: 10px;
    &.router-link-exact-active {
      color: #2c3e50;
      border-bottom: 2px solid orange;
    }
  }
}

#slider {
  display: flex;
  #sliderBtn {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-around;
    height: 452px;
    width: 100px;
    button {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 30px;
      height: 30px;
      border-radius: 50%;
      background-color: #fff;
      border: 0;
      box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    }
    .smallasset img {
      border: 1px solid #eeeeee;
      width: 60px;
      height: 60px;
    }

    div {
      div img {
        width: 100px;
        height: 100px;
      }
    }
  }

  #sliderContent {
    margin: 20px 0 50px 0;
    height: 452px;
    overflow: hidden;
    #sliderImages {
      height: 452px;
      transition: all 0.6s;
      div {
        display: flex;
        justify-content: center;
        img {
          height: 452px;
        }
      }
    }
  }
  #about {
    width: 347px;
    height: 452px;
    padding: 20px 25px;
    display: flex;
    flex-direction: column;
    box-shadow: 0px 13px 22px rgba(228, 228, 228, 0.25);
    border-radius: 5px;
    img {
      width: 95px;
      height: 21px;
    }
    .aboutGray {
      padding: 10px 45px 10px 20px;
      width: 310px;
      height: 48px;
      font-size: 13px;
      color: #383838;
      background-color: #f8f8f8;
      transform: translateX(-10px);
    }
    #aboutPrice {
      display: flex;
      align-items: flex-end;
      margin: 20px 0;
      div {
        width: 100%;
        display: flex;
        flex-direction: column;
      }
      #iBig {
        display: inline-block;
        text-align: center;
        width: 23px;
        height: 23px;
        // padding: 0 0 10px 0;
        font-size: 11px;
        border: 2px solid;
        border-radius: 50%;
      }
    }
    button {
      margin: 0 0 20px 0;
    }
    .aboutSpan {
      margin: 7px;
      font-size: 13px;
    }
  }
}

.yellow {
  text-transform: uppercase;
  font-size: 14px;
  background-color: #ffd637;
  color: #383838;
  border: 0;
  font-weight: bold;
  transition: 0.3s;
  cursor: pointer;
  &:hover {
    background-color: #ffc237;
  }
}

.big {
  width: 297px;
  height: 45px;
  border-radius: 3px;
}

#cards {
  display: flex;
  align-items: center;
  justify-content: space-between;
  .card {
    padding: 20px;
    width: 285px;
    height: 460px;
    background: #ffffff;
    border: 1px solid #ecedef;
    border-radius: 5px;
    div {
      display: flex;
      img {margin-left: 10px;
        width: 15px;
      }
    }
    .cardName {
      display: block;
      font-size: 14px;
      line-height: 120%;
      color: #383838;
      height: 80px;
    }
    span {
      display: block;
    }
    button {
      margin: 25px 0;
      width: 245px;
      height: 45px;
      border-radius: 4px;
    }
  }
}

.sale {
  transform: translateY(-25px);
  position: absolute;
  width: 26px !important;
  height: 26px !important;
  border: 0;
  font-weight: 900;
  color: white;
  background: #F71412;
  border-radius: 4px;
  cursor: pointer;
  transition: .3s;
  &::after {
    content: '';
  }
  &:hover {
    width: 80px !important;
  }
  &:hover::after {
    content: ' Скидка';
  }
}

#footer {
  display: flex;
  height: 200px;
  align-items: center;
  justify-content: space-around;
  background-color: #FFD637;
  input {
    margin: 0 20px;
    width: 250px;
    height: 45px;
    background-color: #ffd637;
    border: 1px solid #383838;
    border-radius: 4px;
    font-size: 14px;
    padding: 10px 19px;
  }
  button {
    width: 182px;
    height: 45px;
    background: #383838;
    border-radius: 4px;
    border: 0;
    color: #ffd637;
    text-transform: uppercase;
    font-size: 14px;
    font-weight: 700;
    cursor: pointer;
    transition: .3s;
    &:hover {
      color: white;
    }
  }

  
}
@media (max-width: 375px) {
    
    #app {
      width: 375px !important;
      overflow-x: hidden;
    }
    #header {
      padding: 0;
      height: 300px;
      flex-direction: column;
      ul {
        flex-direction: column;
        li {
          margin: 2px;
        }
        hr {
          height: 0;
        }
      }
    }
    #search {
      flex-direction: column;
      button {
        margin: 4px;
      }
      input {
        width: 200px !important;
      }
    }
    #menu ul{
      flex-direction: column;
      hr {
        height: 0;
      }
      li {
        margin: 3px 0;
      }
    }
    #slider,
    #cards,
    #footer,
    h2,
    #router, p {
      padding: 20px 0;
      margin: 0  !important;
    }
  #nav{
    width: 100%;
    margin: 0;
    text-align: center;
    padding: 0;
  }
  #slider {
    margin: 0 auto;
    flex-direction: column;
  }
  #about {
    margin: 0 auto;
  }
   #nav,#router {
    display: none;
  }
  h2,p {
    text-align: center;
  }
  #sliderBtn {
    position: absolute;
    z-index: 2;
    top: 1100px;
  }
  #sliderContainer {
    width: 280px;
  }
  #sliderImages {
    width: 280px;
    img {
      padding: 100px 0;
      margin-left: 150px;
      width: 280px;
    }
  }
  #cards {
    flex-direction: column;
    .card {
      margin: 10px 0;
    }
  }
  #footer {
    height: 450px;
    flex-direction: column;
    input {
      margin: 10px 0;
    }

  }
}
  
 
</style>

<script>
export default {
  data() {
    return {
      slide: 0,
    };
  },
  setup() {},
  methods: {
    next() {
      this.slide++;

      if (this.slide == document.querySelectorAll("#sliderImages div").length)
        this.slide = 0;
      // console.log(this.slide);
      document.querySelector(
        "#sliderImages"
      ).style.transform = `translateY(-${this.slide}00%)`;
    },
    back() {
      this.slide--;

      if (this.slide == -1)
        this.slide = document.querySelectorAll("#sliderImages div").length - 1;
      // console.log(this.slide, document.querySelectorAll("#sliderImages div").length);
      document.querySelector(
        "#sliderImages"
      ).style.transform = `translateY(-${this.slide}00%)`;
    },
    show() {
      document.querySelector('#popup').classList.remove('hidden');
      document.querySelector('#popup').classList.add('show');
    },
    hide() {
      document.querySelector('#popup').classList.remove('show');
      document.querySelector('#popup').classList.add('hidden');
    }
  },
};
</script>
