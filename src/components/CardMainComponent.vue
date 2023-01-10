
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
            <p>
                {{ nameComics }}
            </p>
        </div>
   </section>
</template>

<style lang="scss" scoped>
section{ 
  
    color: white;
    div.card-item{
        width: calc(100% / 3 );
        img{
            width: 135px;
        }
    }
}
</style>