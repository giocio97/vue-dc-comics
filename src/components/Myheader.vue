<template>
<header>
  <a href="#">
    <img src="../assets/img/dc-logo.png" alt="logo">
  </a>
  <nav>
    <ul>
    <li v-for="(linkInt,i) in linkInt" :key="i">
     <a :href="linkInt.url">
     {{linkInt.text}}
     </a> </li>

  </ul>
  </nav>
</header>
</template>

<script>
export default {
  name: 'MyHeader',

  data (){
    return{
      linkInt:[
        {
          text: "CHARACTERS",
          url:"#",
          current: false
        },
        {
          text: "COMICS",
          url:"#",
          current: true
        },
        {
          text: "MOVIES",
          url:"#",
          current: false
        },
        {
          text: "TV",
          url:"#",
          current: false
        },
        {
          text: "GAMES",
          url:"#",
          current: false
        },
        {
          text: "COLLECTIBLES",
          url:"#",
          current: false
        },
        {
          text: "VIDEOS",
          url:"#",
          current: false
        },
        {
          text: "FANS",
          url:"#",
          current: false
        },
        {
          text: "NEWS",
          url:"#",
          current: false
        },
        {
          text: "SHOP",
          url:"#",
          current: false
        },
      ]
    }
  }
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
  text-align: center;

  img{
    display: block;
    padding: 10px;
    vertical-align:middle;
  }
  ul{
    list-style-type: none;

    li{
    display: inline-block;
    padding: 10px;

    a{
      text-decoration: none;
      color: grey;
      
      &:hover{
        color: rgb(0, 162, 255);
      }
    }

    
  }
  }
  
}

</style>
