
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
        <div class="card-item">
            <img :src="imgThumb" class="mb-2" alt="" srcset="">
            <p class="text-center">
                {{ nameComics }}
            </p>
        </div>
   </section>
</template>

<style lang="scss" scoped>
section{ 
    color: white;
    div.card-item{
        margin: 1rem;
        width: calc((100% / 6) - 1rem) ;
     
       img{
        width: 150px;
        height: 100%;
        }
      

      p{
        width: 100%;
      }
       
    }
}
</style>