<template>
  <div class="second-half">
    <div class="second-half__vito-block">
      <div class="second-half__background"></div>
      <img src="@/images/Vito.png" alt="" class="second-half__vito-image" />
    </div>
    <div class="second-half__main-content">
      <h2 class="second-half__title">НАБОР «ПОСЫЛКА С КОНТРАБАНДОЙ»</h2>
      <table-block />
      <buy-block />
      <img
        src="@/images/BottomGlow1.png"
        alt=""
        class="second-half__bottom-glow"
      />
    </div>
  </div>
</template>
<script>
import TableBlock from "@/components/TableBlock.vue";
import BuyBlock from "@/components/BuyBlock.vue";
export default {
  components: { TableBlock, BuyBlock },
};
</script>
<style scoped>
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
