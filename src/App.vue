<template>
  <div id="app">
    <header-box :nav="navMenu"/>
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
  },

  data() {
    return {
      navMenu: [
        {
          id: '01',
          label: 'characters',
        },
        {
          id: '02',
          label: 'comics',
        },
        {
          id: '03',
          label: 'movies',
        },
        {
          id: '04',
          label: 'tv',
        },
        {
          id: '05',
          label: 'games',
        },
        {
          id: '06',
          label: 'collectibles',
        },
        {
          id: '07',
          label: 'videos',
        },
        {
          id: '08',
          label: 'fans',
        },
        {
          id: '09',
          label: 'news',
        },
        {
          id: '10',
          label: 'shop',
        },
      ],

    }
  }
}
</script>

<style lang="scss">
@import './style/main.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
</style>
