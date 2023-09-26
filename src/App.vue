<template>
  <div class="page">
    <div class="first-half">
      <!-- <img
        class="first-half__background-image"
        src="@/images/firstHalfBackground.png"
        alt=""
      /> -->
      <img src="@/images/logo.png" alt="" class="first-half__logo" />
      <!-- <div class="first-half__middle-images"> -->
      <img
        src="@/images/MafiaCostume1.png"
        alt=""
        class="first-half__left-mafia"
      />
      <img src="@/images/boxes.png" alt="" class="first-half__boxes" />
      <img
        src="@/images/MafiaCostume2.png"
        alt=""
        class="first-half__right-mafia"
      />
      <!-- </div> -->

      <img src="@/images/glow.png" alt="" class="first-half__middle-glow" />
      <img
        src="@/images/BottomGlow1.png"
        alt=""
        class="first-half__bottom-glow"
      />
      <img
        src="@/images/LayerLeft.png"
        alt=""
        class="first-half__left-shadow"
      />
      <img
        src="@/images/LayerRight.png"
        alt=""
        class="first-half__right-shadow"
      />
      <img
        src="@/images/LayerBottom.png"
        alt=""
        class="first-half__bottom-shadow"
      />
      <div class="first-half__text">
        <h1 class="first-half__header">КОЛЛЕКЦИОННЫЕ ИЗДАНИЯ</h1>
        <p class="first-half__subtitle">
          Побеждайте легко, побеждайте стильно с новыми коллекционными изданиями
          «Аллодов Онлайн»!
        </p>
      </div>
    </div>
    <div class="second-half">
      <div class="second-half__vito-block">
        <div class="second-half__background"></div>
        <img src="@/images/Vito.png" alt="" class="second-half__vito-image" />
      </div>
      <div class="second-half__main-content">
        <h2 class="second-half__title">НАБОР «ПОСЫЛКА С КОНТРАБАНДОЙ»</h2>
        <div class="second-half__table-block">
          <div class="column-names">
            <div class="column-names__free-servers">Бесплатные сервера</div>
            <div class="column-names__subscribe-servers">
              Подписочный сервер
            </div>
          </div>
          <div class="play-time-block">
            <img
              src="@/images/PlayTime.png"
              alt=""
              class="play-time-block__image"
            />
            <div class="play-time-block__title second-half__text">
              Игровое время
            </div>
            <div class="play-time-block__free-servers-count second-half__text">
              -
            </div>
            <div
              class="play-time-block__subscribe-servers-count second-half__text"
            >
              30 дней
            </div>
          </div>
          <div class="toolbox-block">
            <img
              src="@/images/Toolbox.png"
              alt=""
              class="toolbox-block__image"
            />
            <div class="toolbox-block__title second-half__text">
              Запечатанный набор инструментов
            </div>
            <div class="toolbox-block__free-servers-count second-half__text">
              1
            </div>
            <div
              class="toolbox-block__subscribe-servers-count second-half__text"
            >
              1
            </div>
          </div>
          <div class="fragile-rune-block">
            <img
              src="@/images/FragileRune.png"
              alt=""
              class="fragile-rune-block__image"
            />
            <div class="fragile-rune-block__title second-half__text">
              Хрупкая чистая руна <br />
              10-й ступени
            </div>
            <div
              class="fragile-rune-block__free-servers-count second-half__text"
            >
              1
            </div>
            <div
              class="fragile-rune-block__subscribe-servers-count second-half__text"
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
            <div class="big-symbol-block__title second-half__text">
              Большой символ <br />
              изобилия творца
            </div>
            <div class="big-symbol-block__free-servers-count second-half__text">
              10
            </div>
            <div
              class="big-symbol-block__subscribe-servers-count second-half__text"
            >
              -
            </div>
          </div>
          <div class="mana-charge-block">
            <img
              src="@/images/ManaCharge.png"
              alt=""
              class="mana-charge-block__image"
            />
            <div class="mana-charge-block__title second-half__text">
              Мана-батарея
            </div>
            <div
              class="mana-charge-block__free-servers-count second-half__text"
            >
              -
            </div>
            <div
              class="mana-charge-block__subscribe-servers-count second-half__text"
            >
              20
            </div>
          </div>
          <div class="memory-module-block">
            <img
              src="@/images/MemoryModule.png"
              alt=""
              class="memory-module-block__image"
            />
            <div class="memory-module-block__title second-half__text">
              Модуль памяти
            </div>
            <div
              class="memory-module-block__free-servers-count second-half__text"
            >
              -
            </div>
            <div
              class="memory-module-block__subscribe-servers-count second-half__text"
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
            <div class="vito-support-block__title second-half__text">
              Помощник Вито
            </div>
            <div
              class="vito-support-block__free-servers-count second-half__text"
            >
              1
            </div>
            <div
              class="vito-support-block__subscribe-servers-count second-half__text"
            >
              1
            </div>
          </div>
        </div>
        <div class="second-half__buy-block">
          <img src="@/images/Box.png" alt="" class="second-half__box" />
          <div class="second-half__price-block">
            <p class="second-half__price">399 ₽</p>
            <p class="second-half__buy-now">ПРИОБРЕСТИ</p>
          </div>
        </div>
        <img
          src="@/images/BottomGlow1.png"
          alt=""
          class="second-half__bottom-glow"
        />
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Roboto&family=Roboto+Condensed:wght@400;700&display=swap");
body {
  background-color: #2b2b2b;
  margin-bottom: 20px;
  margin-top: 20px;
}
.page {
  position: relative;
}
.first-half {
  position: relative;
  margin: 0 auto;
  max-width: 1920px;
  height: 892px;
  background-image: url("~@/images/firstHalfBackground.png");

  overflow: hidden;
}
.first-half__background-image {
  max-width: 1920px;
  max-height: 892px;
  position: absolute;
  left: 0;
  top: 0;
  z-index: -1;
}
.first-half__logo {
  max-width: 376px;
  max-height: 348px;

  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  z-index: 4;
}
.first-half__left-mafia {
  max-width: 577px;
  max-height: 876px;
  position: absolute;
  left: 0;
  bottom: 0;
  z-index: 1;
}
.first-half__right-mafia {
  max-width: 678px;
  max-height: 876px;
  position: absolute;
  right: 1%;
  bottom: 0;
  z-index: 1;
}
.first-half__boxes {
  max-width: 766px;
  max-height: 525px;
  position: absolute;
  top: 55.5%;
  left: 48.8%;
  transform: translate(-50%, -50%);
  z-index: 4;

  align-self: flex-end;
}
.first-half__middle-glow {
  position: absolute;
  top: 50%;
  left: 52%;
  transform: translate(-50%, -50%);
  z-index: 3;
  width: 2006px;
  height: 892px;
  mix-blend-mode: screen;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}
.first-half__bottom-glow {
  position: absolute;
  min-width: 1977px;
  min-height: 172px;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  z-index: 3;
}
.first-half__left-shadow {
  max-width: 462px;
  max-height: 934px;
  mix-blend-mode: multiply;
  box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.25);
}
.first-half__right-shadow {
  max-width: 462px;
  max-height: 934px;
  position: absolute;
  right: 0;
  mix-blend-mode: multiply;
}
.first-half__bottom-shadow {
  max-width: 100%;
  max-height: 380px;
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  mix-blend-mode: multiply;
  z-index: 2;
}
.first-half__text {
  position: absolute;
  bottom: 4.5%;
  left: 50.7%;
  transform: translateX(-50%);
  display: flex;
  flex-direction: column;
  z-index: 4;
}
.first-half__header {
  color: #fff;
  text-align: center;
  text-shadow: 0px 4px 4px rgba(0, 0, 0, 0.25);
  font-family: "Roboto Condensed", sans-serif;
  font-size: 42px;
  font-style: normal;
  font-weight: 700;
  line-height: 4px;
  -webkit-text-stroke: 1px black;
  margin: 0;
  margin-bottom: 25px;
}
.first-half__subtitle {
  color: #fff;
  text-align: center;
  font-family: "Roboto", sans-serif;
  font-size: 20px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  white-space: nowrap;
  margin-left: -17px;
}

.second-half {
  background-image: url("~@/images/BackgrounWall.png");
  padding-top: 31px;
  max-width: 1920px;
  min-height: 1024px;
  display: flex;
  margin: 0 auto;
  overflow: hidden;
  margin-bottom: 10px;
}

.second-half__vito-block {
  position: relative;
  width: 50%;
}
.second-half__background {
  position: absolute;
  left: 225px;
  bottom: 156px;
  width: 680px;
  height: 686px;
  border-radius: 686px;
  border: 1px solid #000;
  opacity: 0.2;
  background: #416df4;
  mix-blend-mode: lighten;
  filter: blur(100px);
}
.second-half__vito-image {
  position: absolute;
  left: 359px;
  bottom: 133px;
  z-index: 2;
}
.second-half__main-content {
  width: 50%;
}
.second-half__title {
  color: #416df4;
  font-family: "Roboto Condensed", sans-serif;
  font-size: 30px;
  font-style: normal;
  font-weight: 700;
  line-height: normal;
  margin-top: 27px;
  margin-bottom: 39px;
}
.second-half__table-block {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
}
.second-half__text {
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

.second-half__buy-block {
  display: flex;
}
.second-half__box {
  margin-right: 35px;
}
.second-half__price-block {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
}
.second-half__price {
  color: #fff;
  font-family: "Roboto", sans-serif;
  font-size: 50px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  margin: 0;
}
.second-half__buy-now {
  color: #000;
  text-align: center;
  font-family: Roboto;
  font-size: 16px;
  font-style: normal;
  font-weight: 400;
  line-height: normal;
  border-radius: 7px;
  padding: 10.5px 0px;
  width: 180px;
  background: #fcff00;
  margin-top: 10px;
  margin-bottom: 32px;
}
.second-half__bottom-glow {
  position: absolute;
  min-width: 1977px;
  min-height: 172px;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
  z-index: 0;
}
</style>
