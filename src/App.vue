<script>
import HeaderDcComics from './components/HeaderDcComics.vue'
import MainDcComics from './components/MainDcComics.vue'
import FooterDcComics from './components/FooterDcComics.vue'

export default {

  components:{
     HeaderDcComics,
     MainDcComics,
     FooterDcComics,

  }
 
}

</script>

<template>
 <HeaderDcComics />
 <MainDcComics />
 <FooterDcComics />
</template>

<style lang="scss">
@use './style/general.scss' as *;
@use '../node_modules/bootstrap/scss/bootstrap.scss' as *;

</style>

