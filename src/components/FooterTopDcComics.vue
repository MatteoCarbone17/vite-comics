<script>
export default{
    data(){
        return{
           dcComicsList:[
           {
               text:"Dc comics",
                url: "#",
                active: false,
            },
            {
               text:"Characters",
                url: "#",
                active: false,
            },
            {
                text:"Comics",
                url: "#",
                active: false,
            },
            {
                text:"Movies",
                url: "#",
                active: false,
            },
            {
                text:"TV",
                url: "#",
                active: false,
            },
            {
                text:"Games",
                url: "#",
                active: false,
            },
            {
                text:"Videos",
                url: "#",
                active: false,
            },
            {
                text:"News",
                url: "#",
                active: false,
            },
            

           ],
           dcList:[
           {
               text:"dc",
                url: "#",
                active: false,
            },
            {
               text:"Team of use",
                url: "#",
                active: false,
            },
            {
                text:"Privacy policy (New)",
                url: "#",
                active: false,
            },
            {
                text:"Ad Choices",
                url: "#",
                active: false,
            },
            {
                text:"Advertising",
                url: "#",
                active: false,
            },
            {
                text:"Jobs",
                url: "#",
                active: false,
            },
            {
                text:"Subscriptions",
                url: "#",
                active: false,
            },
            {
                text:"Talent Workshops",
                url: "#",
                active: false,
            },
            {
                text:"CPSC Certificates",
                url: "#",
                active: false,
            },
            {
                text:"Ratings",
                url: "#",
                active: false,
            },
            {
                text:"Shop Help",
                url: "#",
                active: false,
            },
            {
                text:"Contact Us",
                url: "#",
                active: false,
            },
            
            

           ],
           sitesList:[
           {
               text:"sites",
                url: "#",
                active: false,
            },
            {
               text:"DC",
                url: "#",
                active: false,
            },
            {
                text:"MAD Magazine",
                url: "#",
                active: false,
            },
            {
                text:"DC Kids",
                url: "#",
                active: false,
            },
            {
                text:"DC Universe",
                url: "#",
                active: false,
            },
            {
                text:"DC Power Visa",
                url: "#",
                active: false,
            },
            
            
            

           ],
        }
    }
 }
</script>

<template>
    <section>
        <div class="container-fluid">
            <div class="row text-light">
                <div class="col-7 d-flex justify-content-center">
                    <ul>
                        <li v-for="navItem in dcComicsList" >
                            {{ navItem.text  }}
                        </li>
                    </ul>
                    <ul>
                        <li v-for="navItem in dcList">
                            {{ navItem.text  }}
                        </li>
                    </ul>
                    <ul>
                        <li v-for="navItem in sitesList">
                            {{ navItem.text  }}
                        </li>
                    </ul>
                </div>
                <div class="col-5">
                    <img src="../assets/img/dc-logo-bg.png" class="img-fluid"  alt="" srcset="">
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
    
    section{
        background-image: url(../assets/img/footer-bg.jpg);
        background-position: center;
        background-size: contain;
    }

   ul{
    padding: 2rem;
    li{
        list-style-type: none;
        color: rgb(147, 147, 148);
    }
     :first-child{
        font-size: 1.2rem;
        text-transform: uppercase;
        color: white;
       
     }
   }

   img{
    width: 400px;
   }
</style>
