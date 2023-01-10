<script>
 export default{
    data(){
        return{
          logoList:[
            {
                
                url:"facebook.png",
            
            },
            {
                url:"twitter.png",
               
               
            },
            {
                url:"youtube.png",
              
               
            },
            {
                url:"pinterest.png",
               
               
            },
            {
                url:"periscope.png",
               
              
            },
            

           ]
        }
    }
 }
</script>

<template>
    <section>
        <div class="container-fluid">
            <div class="row align-items-center">
                <div class="col-5 d-flex justify-content-center">
                    <button>SING-UP NOW!</button>
                </div>
                <div class="col-7">
                    <ul class="d-flex justify-content-center">
                        <li>
                            follow us
                        </li>
                        <li v-for="logo in logoList " >
                            <img :src="`../src/assets/img/footer-${logo.url}`" alt="">
                        </li>
                    </ul>
                </div>
            </div>
            
        </div>
    </section>
</template>

<style lang="scss" scoped>

section{
    background-color: rgb(48, 48, 48);
}

.row{
    height: 100px;
}

button{
    padding: .7rem;
    border-color: rgb(2, 130, 249);
    background-color: rgb(48, 48, 48);
    color: white;
}

 ul{
    li{
        list-style-type: none;
        padding-left: 1.3rem;
        
    }

     :first-child{
        font-size: 1.3rem;
        font-weight: 600;
        text-transform: uppercase;
        color:rgb(2, 130, 249);
       
     }

   }

  
   
</style>