
<script>
export default {
    name : 'CardMainComponent',
    props: {
        imgThumb: String ,
        nameComics: String,
        price: Number,
        typeComics: String,
        
    },
}
</script>


<template>
   <section>
        <div class="img-wrapper d-flex justify-content-center ">
            <img :src="imgThumb" class="" alt="" srcset="">
        </div>
        <p class="text-center">
            {{ nameComics }}
        </p>
     </section>
</template>

<style lang="scss" scoped>
section{ 
    width: calc((100% / 6) - 2rem ) ;
    color: white;
    margin: 1rem;
    height: 240px;
    div.img-wrapper{
        img{
            width: 100%;
        }
    }
}
</style>