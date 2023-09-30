<template>
  <div class="table-block">
    <div class="column-names">
      <div class="column-names__free-servers">Бесплатные сервера</div>
      <div class="column-names__subscribe-servers">Подписочный сервер</div>
    </div>
    <div class="play-time-block">
      <img src="@/images/PlayTime.png" alt="" class="play-time-block__image" />
      <div class="play-time-block__title table-block__text">Игровое время</div>
      <div class="play-time-block__free-servers-count table-block__text">-</div>
      <div class="play-time-block__subscribe-servers-count table-block__text">
        30 дней
      </div>
    </div>
    <div class="toolbox-block">
      <img src="@/images/Toolbox.png" alt="" class="toolbox-block__image" />
      <div class="toolbox-block__title table-block__text">
        Запечатанный набор инструментов
      </div>
      <div class="toolbox-block__free-servers-count table-block__text">1</div>
      <div class="toolbox-block__subscribe-servers-count table-block__text">
        1
      </div>
    </div>
    <div class="fragile-rune-block">
      <img
        src="@/images/FragileRune.png"
        alt=""
        class="fragile-rune-block__image"
      />
      <div class="fragile-rune-block__title table-block__text">
        Хрупкая чистая руна <br />
        10-й ступени
      </div>
      <div class="fragile-rune-block__free-servers-count table-block__text">
        1
      </div>
      <div
        class="fragile-rune-block__subscribe-servers-count table-block__text"
      >
        -
      </div>
    </div>
    <div class="big-symbol-block">
      <img
        src="@/images/BigSymbol.png"
        alt=""
        class="big-symbol-block__image"
      />
      <div class="big-symbol-block__title table-block__text">
        Большой символ <br />
        изобилия творца
      </div>
      <div class="big-symbol-block__free-servers-count table-block__text">
        10
      </div>
      <div class="big-symbol-block__subscribe-servers-count table-block__text">
        -
      </div>
    </div>
    <div class="mana-charge-block">
      <img
        src="@/images/ManaCharge.png"
        alt=""
        class="mana-charge-block__image"
      />
      <div class="mana-charge-block__title table-block__text">Мана-батарея</div>
      <div class="mana-charge-block__free-servers-count table-block__text">
        -
      </div>
      <div class="mana-charge-block__subscribe-servers-count table-block__text">
        20
      </div>
    </div>
    <div class="memory-module-block">
      <img
        src="@/images/MemoryModule.png"
        alt=""
        class="memory-module-block__image"
      />
      <div class="memory-module-block__title table-block__text">
        Модуль памяти
      </div>
      <div class="memory-module-block__free-servers-count table-block__text">
        -
      </div>
      <div
        class="memory-module-block__subscribe-servers-count table-block__text"
      >
        10
      </div>
    </div>
    <div class="vito-support-block">
      <img
        src="@/images/VitoSupport.png"
        alt=""
        class="vito-support-block__image"
      />
      <div class="vito-support-block__title table-block__text">
        Помощник Вито
      </div>
      <div class="vito-support-block__free-servers-count table-block__text">
        1
      </div>
      <div
        class="vito-support-block__subscribe-servers-count table-block__text"
      >
        1
      </div>
    </div>
  </div>
</template>

<style scoped>
.table-block {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
}
.table-block__text {
  font-family: "Roboto", sans-serif;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
}
.column-names {
  color: #671d00;
  display: grid;
  grid-template-columns: auto auto 140px 140px;
  grid-row: 1;
  margin-bottom: 9px;
  gap: 11px;
}

.column-names__free-servers {
  grid-column: 3;
  grid-row: 1;
  border: 1px solid rgba(103, 29, 0, 0.48);
  background: rgba(0, 0, 0, 0.55);

  color: #671d00;
  text-align: center;
  font-family: Roboto;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  padding: 4px 0px;
}
.column-names__subscribe-servers {
  grid-column: 4;
  grid-row: 1;
  border: 1px solid rgba(103, 29, 0, 0.48);
  background: rgba(0, 0, 0, 0.55);
  color: #671d00;
  text-align: center;
  font-family: Roboto;
  font-size: 12px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  padding: 5px 0px;
}
.play-time-block,
.toolbox-block,
.fragile-rune-block,
.big-symbol-block,
.mana-charge-block,
.memory-module-block,
.vito-support-block {
  display: grid;
  color: #fff;
  grid-template-columns: 62px 229px 140px 140px;
  align-items: center;
  justify-items: center;
  border-radius: 1px;
  border: 1px solid rgba(103, 29, 0, 0.48);
  background: rgba(0, 0, 0, 0.55);
  margin-bottom: 1px;
}
.play-time-block {
  padding: 5px 0px 4px 6px;
  grid-row: 2;
}
.play-time-block__image {
  grid-column: 1;
}
.play-time-block__title {
  justify-self: left;
  padding-left: 20px;
  grid-column: 2;
}
.play-time-block__free-servers-count {
  grid-column: 3;
}
.play-time-block__subscribe-servers-count {
  grid-column: 4;
}
.toolbox-block {
  padding: 5px 5px 5px 5px;
  grid-row: 3;
}
.toolbox-block__image {
  grid-column: 1;
}
.toolbox-block__title {
  justify-self: left;
  padding-left: 20px;
  grid-column: 2;
}
.toolbox-block__free-servers-count {
  grid-column: 3;
}
.toolbox-block__subscribe-servers-count {
  grid-column: 4;
}
.fragile-rune-block {
  padding: 6px 0px 6px 6px;
  grid-row: 4;
}
.fragile-rune-block__image {
  grid-column: 1;
}
.fragile-rune-block__title {
  justify-self: left;
  padding-left: 20px;
  grid-column: 2;
}
.fragile-rune-block__free-servers-count {
  grid-column: 3;
}
.fragile-rune-block__subscribe-servers-count {
  grid-column: 4;
}
.big-symbol-block {
  padding: 6px 0px 6px 6px;
  grid-row: 5;
}
.big-symbol-block__image {
  grid-column: 1;
}
.big-symbol-block__title {
  justify-self: left;
  padding-left: 20px;
  grid-column: 2;
}
.big-symbol-block__free-servers-count {
  grid-column: 3;
}
.big-symbol-block__subscribe-servers-count {
  grid-column: 4;
}
.mana-charge-block {
  padding: 5px 0px 5px 5px;
  grid-row: 6;
}
.mana-charge-block__image {
  grid-column: 1;
}
.mana-charge-block__title {
  justify-self: left;
  padding-left: 20px;
  grid-column: 2;
}
.mana-charge-block__free-servers-count {
  grid-column: 3;
}
.mana-charge-block__subscribe-servers-count {
  grid-column: 4;
}
.memory-module-block {
  padding: 5px 0px 5px 5px;
  grid-row: 7;
}
.memory-module-block__image {
  grid-column: 1;
}
.memory-module-block__title {
  justify-self: left;
  padding-left: 20px;
  grid-column: 2;
}
.memory-module-block__free-servers-count {
  grid-column: 3;
}
.memory-module-block__subscribe-servers-count {
  grid-column: 4;
}
.vito-support-block {
  padding: 5px 0px 5px 5px;
  grid-row: 8;
  margin-bottom: 34px;
}
.vito-support-block__image {
  grid-column: 1;
}
.vito-support-block__title {
  justify-self: left;
  padding-left: 20px;
  grid-column: 2;
}
.vito-support-block__free-servers-count {
  grid-column: 3;
}
.vito-support-block__subscribe-servers-count {
  grid-column: 4;
}
</style>
