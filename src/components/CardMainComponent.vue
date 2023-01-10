
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
    width: calc(100% / 6) ;
    color: white;

    div.img-wrapper{
        height: 150px;
        width: 150px;

        img{
            width: 100%;
        }
    }
}
</style>