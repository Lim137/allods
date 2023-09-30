<template>
  <div class="second-half__buy-block">
    <img src="@/images/Box.png" alt="" class="second-half__box" />
    <div class="second-half__price-block">
      <p class="second-half__price">399 ₽</p>
      <p class="second-half__buy-now">ПРИОБРЕСТИ</p>
    </div>
  </div>
</template>
<style scoped>
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
</style>
