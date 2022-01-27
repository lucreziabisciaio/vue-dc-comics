<template>
  <div id="app">
    <header-box />
    <main-box />
    <footer-top />
    <footer-main />
    <footer-bottom />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue';
import MainBox from './components/MainBox.vue';
import FooterTop from './components/FooterTop.vue';
import FooterMain from './components/FooterMain.vue';
import FooterBottom from './components/FooterBottom.vue';

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
    FooterTop,
    FooterMain,
    FooterBottom,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
</style>
