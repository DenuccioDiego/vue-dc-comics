<template>
     
     <div id="footer_top">
          <div class="container d-flex" >
               <div class="d-flex link_utili">
                    <div>
                         <div>
                              <span>
                                   DC COMICS
                              </span>
                              <li>lorem</li>
                              <li>lorem</li>
                              <li>lorem</li>
                              <li>lorem</li>
                              <li>lorem</li>
                              <li>lorem</li>

                         </div>
                         
                         <div>
                              <span>
                                   SHOP
                              </span>
                              <li>Shop DC</li>
                              <li>Shop Dc colletctibles</li>
                         </div>
                         
                    </div>

                    <div>
                         <span>
                              DC
                         </span>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                    </div>
                    <div>
                         <span>
                              SITES
                         </span>

                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>
                         <li>lorem</li>

                    </div>
               </div>

               <div class="image_logo_footer">
                    
               </div>

          </div>
     </div>

</template>

<script>


export default {
     
}
</script>

<style scoped lang="scss">

#footer_top{
     background-image: url("../assets/img/footer-bg.jpg");
     background-repeat: no-repeat;
     background-size: cover;
     height: 35vh;
}

.container{
    height: 35vh;
}

.link_utili{
     width: 40%;
}

.image_logo_footer{
     width: 60%;
     background-image: url("../assets/img/dc-logo-bg.png");
     background-repeat: no-repeat;
     background-position: center;
     
}

.link_utili>div{
     width: calc(100% / 3);
     padding-top: 30px;
}

li{
     padding: 2px;
     color: grey;
}

span{
     color: white;
     font-size: 1.25rem;
     line-height: 50px;
}
</style>
