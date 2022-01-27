<template>
  <div id="app">
    <header-box />
    <main-box />
    <footer-top />
    <footer-main />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue';
import MainBox from './components/MainBox.vue';
import FooterTop from './components/FooterTop.vue';
import FooterMain from './components/FooterMain.vue';

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
    FooterTop,
    FooterMain,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
</style>
