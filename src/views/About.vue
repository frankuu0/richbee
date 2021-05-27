<template>
  <div>
    <ul id="table">
      <li style="width:350px">Адрес</li>
      <li>График работы</li>
      <li>Наличие</li>
      <li>Телефон</li>
    </ul>
    <div>
      <ul class="descTable gray">
        <li class="margin">
          <span style="font-weight:bold">Центральный склад</span><br><br />Приморский край, ст. Жулевская,
          ул. Транспортная, 5-Г. Магазин находится в головном здании.
        </li>
        <li class="listElem">Пн-пт<br />7:00 - 17:00</li>
        <li class="listElemS"><span class="green">В наличии</span></li>
        <li class="listElem">8-(800) 251-44-75</li>
      </ul>
    </div>
    <div>
      <ul class="descTable white">
        <li class="margin">
          <span style="font-weight:bold">м Октябрьское поле</span><br><br />Город Москва, ул. Народного
          Ополчения, 48 корпус 1
        </li>
        <li class="listElem">Пн-вс<br />круглосуточно</li>
        <li class="listElemS"><span class="green">В наличии</span></li>
        <li class="listElem">8-(800) 251-44-75</li>
      </ul>
    </div>
    <div>
      <ul class="descTable gray">
        <li class="margin">
          <span style="font-weight:bold">м Петровско-Разумовская</span><br><br />Город Москва, ул. Линии
          Октябрьской Железной Дороги, д. 2с2
        </li>
        <li class="listElem">Пн-вс<br />круглосуточно</li>
        <li class="listElemS"><span class="green">В наличии</span></li>
        <li class="listElem">8-(800) 251-44-75</li>
      </ul>
    </div>
    <div>
      <ul class="descTable white">
        <li class="margin">
          <span style="font-weight:bold">м Профсоюзная</span><br><br />Город Москва Ломоносовский просп., д.
          5
        </li>
        <li class="listElem">Пн-вс<br />круглосуточно</li>
        <li class="listElemS"><span>Нет в наличии</span></li>
        <li class="listElem">8-(800) 251-44-75</li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss">
#table {
  list-style-type: none;
  display: flex;
  justify-content: space-around;
  font-weight: 500;
  font-size: 20px;
  line-height: 23px;
  color: #797979;
}
.margin {
  width: 468px;
}
.listElemS{
  width: 120px;
  text-align: center;
}
.listElem {
  width: 130px;
}
.descTable {
  display: flex;
  list-style-type: none;
  justify-content: space-around;
  align-items: center;
  height: 138px;
  color: #0b0b0b;
}
.gray {
  background-color: #f8f8f8;
}
.white {
  background-color: #fff;
}

.green {
  color: #32A73C;
}
</style>
