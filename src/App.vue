<script>
import HeaderDcComics from './components/HeaderDcComics.vue'
import MainDcComics from './components/MainDcComics.vue'
import FooterHighDcComics from './components/FooterHighDcComics.vue'
import FooterLowDcComics from './components/FooterLowDcComics.vue'
export default {

  components:{
     HeaderDcComics,
     MainDcComics,
     FooterHighDcComics,
     FooterLowDcComics,

  }
 
}

</script>

<template>

  <header>
    <HeaderDcComics />
  </header>
  <main>
    <MainDcComics />
  </main>

  <footer class="fixed-bottom" >
    <FooterHighDcComics />
    <FooterLowDcComics />
  </footer>
 
</template>

<style lang="scss">
@use './style/general.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;

</style>

