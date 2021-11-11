<template>

     <div id="footer_bot">
          <div class="container d-flex">
               <div>
                    <a href="">SIGN-UP NOW!</a>
               </div>

               <div class="d-flex align-items-center">
                    <span>FOLLOW US</span>
                    <div><img src="../assets/img/footer-facebook.png" alt=""></div>
                    <div><img src="../assets/img/footer-twitter.png" alt=""></div>
                    <div><img src="../assets/img/footer-youtube.png" alt=""></div>
                    <div><img src="../assets/img/footer-pinterest.png" alt=""></div>
                    <div><img src="../assets/img/footer-periscope.png" alt=""></div>
               </div>
          </div>

     </div>

</template>

<script>


export default{
     
}
</script>

<style scoped lang="scss">

#footer_bot{
     background-color: #303030;
     height: 16.5vh;
     padding-top: 5rem;
     font-size: 1.25rem;

     &>div{
          justify-content: space-between;
          align-items: baseline;
     }

}

span{
     color: #0282f9;
     
}

a{
    color: white;
    border: 2px solid #0282f9;
    padding: 0.75rem;
}

img{
     padding-left: 20px;
}
</style>
