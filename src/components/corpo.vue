<template>
<main>
 <div class="jumbo">
<h2>Content goes here</h2>
 </div>
 <div class="prodotti">
     <div v-for="(linkMain,i) in linkMain" :key="i" class="prodotto">
         <img :src="linkMain.img" :alt="linkMain.text">
         <span>{{linkMain.text}}</span>
     </div>
 </div>
</main>
</template>

<script>
export default {
  name: 'MyCorpo',

   data (){
    return{
      linkMain:[
        {
          text: "DIGITAL COMICS",
         
          img:require ("../assets/img/buy-comics-digital-comics.png")
        },
        {
          text: "DC MERCHANDISE",
         
          img:require("../assets/img/buy-comics-merchandise.png")
        },
        {
          text: "SUBSCRIPTION",
          
          img: require("../assets/img/buy-comics-subscriptions.png")
        },
        {
          text: "COMIC SHOP LOCATOR",
         
          img:require("../assets/img/buy-comics-shop-locator.png")
        },
        {
          text: "DC POWER VISA",
         
          img: require("../assets/img/buy-dc-power-visa.svg")
        },
        
      ]
    }
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
main{

  
    .jumbo{
        width: 100%;
        height: 10vh;
        background-color: black;
         
         h2 {
           
           text-align: left;
         margin-left: 100px;
         padding: 20px;
            color: rgb(255, 255, 255);
        }
           
    }

    .prodotti{
        background-color: #0282f9;
        color: white;
        display: flex;
        justify-content: center;

        .prodotto{
            display: flex;
           align-items:center;
           padding: 20px;
           
           span{
               padding: 10px;
           }

           img{
               width: 60px;
               height: 60px;
               object-fit: contain;
           }
        }
    }
}

</style>
