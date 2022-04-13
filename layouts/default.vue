<template>
  <div>
    <TheHeader></TheHeader>
    <div id="menu" class="fas fa-bars"></div>
    <Nuxt />
    <a href="#home" class="top">
      <img src="images/scroll-top-img.png" alt="" />
    </a>
  </div>
</template>

<script>
import TheHeader from "./TheHeader.vue";

export default {
  components: {
    TheHeader,
  },
};
</script>