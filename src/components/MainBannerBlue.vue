
<script>
export default {
data() {
    return {
        bannerBlueItem :[
            {
                image: 'buy-comics-digital-comics.png',
                text: 'digital comics'
            },
            {
                image: 'buy-comics-merchandise.png',
                text: 'dc merchandise'
            },
            {
                image: 'buy-comics-shop-locator.png',
                text: 'comic shop locator'
            },
            {
                image: 'buy-comics-subscriptions.png',
                text: 'subscriptions'
            },
            {
                image: 'buy-dc-power-visa.svg',
                text: 'comic shop locator'
            },
        ]

  }
},
methods: {
    getImagePath: function(imgPath) {
        return new URL(`../assets/img/${imgPath}`, import.meta.url).href;
    }
}    
}
</script>
<template>
    <div  class="div-banner d-flex justify-content-center align-items-center" >
        <div class="d-flex align-items-center" v-for="item in  bannerBlueItem" > 
            <img :src="getImagePath(item.image ) " :alt=" item.text  ">
            <p class="text-light ms-2">
                {{ item.text  }}
            </p>
        </div>
    </div>
</template>



<style lang="scss" scoped >
    .div-banner{
        background-color: rgb(2, 130, 249);
        height: 270px;
    }

    img{
        height: 60px;
        margin-left: 3rem;
    }
</style>