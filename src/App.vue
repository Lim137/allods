<template>
  <div class="page">
    <first-half />
    <second-half />
  </div>
</template>

<script>
import FirstHalf from "@/components/FirstHalf.vue";
import SecondHalf from "@/components/SecondHalf.vue";
export default {
  name: "App",
  components: {
    FirstHalf,
    SecondHalf,
  },
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
</style>
