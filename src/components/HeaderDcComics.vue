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
                active: false,
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
    <div class="row">
        <div class="col-5 d-flex justify-content-center">
            <img src="../assets/img/dc-logo.png" class="p-3"  alt="" srcset="">
        </div>
        <div class="col-7">
            <ul class="d-flex p-5">
                <li class="fs-6 ms-4 " v-for="navItem in HeaderNavItems" >
                    {{ navItem.text }}
                </li>
            </ul>
        </div>

    </div>
 </section>
</template>

<style lang="scss" scoped >

img{
    max-width: 100%;
}

li{
    list-style-type: none;
    
}

</style>
