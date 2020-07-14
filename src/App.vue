<template>
<div class="app">
  <header-vue></header-vue>
  <main-page-vue></main-page-vue>
  <footer-vue></footer-vue>
</div>
</template>

<script>
import HeaderVue from "./components/Header.vue";
import FooterVue from "./components/Footer.vue";
import MainPageVue from "./components/MainPage.vue";

export default {
  name: "app",
  components: {
    HeaderVue,
    FooterVue,
    MainPageVue
  }
};
</script>

<style>
.sidenav-overlay {
  z-index: 100 !important;
}
</style>