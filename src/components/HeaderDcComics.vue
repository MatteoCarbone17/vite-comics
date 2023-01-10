<script>
   
 export default{
    data(){
        return{
           HeaderNavItems:[
            {
                text:"CHARACTERS",
                url: "#",
                active: false,
            },
            {
                text:"COMICS",
                url: "#",
                active: false,
            },
            {
                text:"MOVIES",
                url: "#",
                active: true,
            },
            {
                text:"TV",
                url: "#",
                active: false,
            },
            {
                text:"GAMES",
                url: "#",
                active: false,
            },
            {
                text:"COLLECTIBLES",
                url: "#",
                active: false,
            },
            {
                text:"VIDEOS",
                url: "#",
                active: false,
            },
            {
                text:"FANS",
                url: "#",
                active: false,
            },
            {
                text:"NEWS",
                url: "#",
                active: false,
            },
            {
                text:"SHOP",
                url: "#",
                active: false,
            },

           ]
        }
    }
 }

</script>

<template>
 <section class="container-fluid">
    <div class="row pt-2">
        <div class="col-5 wrapper d-flex  align-items-center justify-content-center">
            <img src="../assets/img/dc-logo.png" alt="" srcset="">
        </div>
        <div class="col-7">
            <ul class="d-flex wrapper">
                <li class="d-flex align-items-center justify-content-center" v-for="navItem in HeaderNavItems" >
                    {{ navItem.text }}
                </li>
            </ul>
        </div>
    </div>
 </section>
</template>

<style lang="scss" scoped >

.wrapper{
    height: 100px;
}

img{
    height: 80%;
}
li{
    list-style-type: none;
    line-height: 100px;
    margin-right: 1rem;
    &:hover{
         border-bottom:  rgb(2, 130, 249) 2px solid ;
    }
   
    
}

</style>
