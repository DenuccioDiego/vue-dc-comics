<template>

     <div class="d-flex" id="card">

          <div>  
               <img src="../assets/img/buy-comics-digital-comics.png" ><span>DIGITAL COMICS</span>
          </div>

          <div> 
               <img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span>
          </div>

          <div> 
               <img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>SUBSCRIPTIONS</span>
          </div>

          <div> 
               <img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>COMIC SHOP LOCATOR</span>
          </div>

          <div> 
               <img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span>
          </div>

     </div>   

</template>

<script>


export default {
                    
}
</script>

<style scoped lang="scss">



#card {
     padding: 2rem;
     justify-content: space-between;
     
     & div{
          display: flex;
          width: calc(100% / 5);
          align-items: center;
          
     }

     & img{
          height: 6rem;
     }
     & span{
          color: white;
          font-size: 0.8rem;
          padding-left: 5px;
     }
}


 

</style>