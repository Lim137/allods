<template>
  <div class="first-half">
    <img src="@/images/logo.png" alt="" class="first-half__logo" />
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

    <img src="@/images/glow.png" alt="" class="first-half__middle-glow" />
    <img
      src="@/images/BottomGlow1.png"
      alt=""
      class="first-half__bottom-glow"
    />
    <img src="@/images/LayerLeft.png" alt="" class="first-half__left-shadow" />
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
</template>
<style scoped>
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
</style>
