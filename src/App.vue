<template>
  <div id="app">
    <header-box />
    <main-box />
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue';
import MainBox from './components/MainBox.vue';

export default {
  name: 'App',
  components: {
    HeaderBox,
    MainBox,
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
</style>
