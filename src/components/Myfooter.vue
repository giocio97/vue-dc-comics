<template>
<footer>
  <section class="footlist">
    <div class="lista-componenti">
      <div>
          <h4>DC COMICS</h4>
          <ul>
            <li>vari</li>
            <li>vari</li>
            <li>vari</li>
            <li>vari</li>
        </ul>
      </div>
      
    </div>
    <img src="../assets/img/dc-logo-bg.png" alt="logo-bg-dc">
  </section>
  <section class="log-social">
    <h4 class="login">SIGN-UP NOW!</h4>
    <div class="profili-social">
        <h4 class="social">FOLLOW US</h4>
        <img src="../assets/img/footer-facebook.png" alt="fb">
        <img src="../assets/img/footer-twitter.png" alt="twitter">
        <img src="../assets/img/footer-youtube.png" alt="yt">
        <img src="../assets/img/footer-pinterest.png" alt="pinterest">
        <img src="../assets/img/footer-periscope.png" alt="periscope">
    </div>
  </section>

</footer>
</template>

<script>
export default {
  name: 'MyFooter',
 
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
footer{
  .footlist{
    display: flex;
    justify-content: space-around;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: 100%;
    background-repeat: no-repeat;
    
    .lista-componenti{
      color: white;
     ul{
        list-style-type: none;
     }
    }
  img{
    object-fit: cover;
    
    
  }
  }

  .log-social{
    background-color: #303030;
    display: flex;
    justify-content: space-around;

.login{
      padding: 10px;
      border: solid 1px #175e9b ;
      color: white;
    }

.profili-social{
  display: flex;
  justify-content: space-around;

  
    .social{
      color:#175e9b;
      
    }
    img{
      width: 100%;
      object-fit: contain;
      padding: 10px;

      
      
    }

}


  }
}

</style>
