<template>
  <div id="app">
    <header-box />
    <main-box />
    <footer-top />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue';
import MainBox from './components/MainBox.vue';
import FooterTop from './components/FooterTop.vue';

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
    FooterTop,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
</style>
