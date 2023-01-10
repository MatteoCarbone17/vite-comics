<script>
import HeaderDcComics from './components/HeaderDcComics.vue'
import MainDcComics from './components/MainDcComics.vue'
import FooterTopDcComics from './components/FooterTopDcComics.vue'
import FooterBottomDcComics from './components/FooterBottomDcComics.vue'
import MainBannerBlue from './components/MainBannerBlue.vue';
export default {

  components:{
     HeaderDcComics,
     MainDcComics,
     FooterTopDcComics,
     FooterBottomDcComics,
     MainBannerBlue,
  }
 
}

</script>

<template>

  <header>
    <HeaderDcComics />
  </header>
  <main>
    <MainDcComics />
    <MainBannerBlue />
  </main>

  <footer>
    <FooterTopDcComics />
    <FooterBottomDcComics />
  </footer>
 
</template>

<style lang="scss">
@use './style/general.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;

</style>

