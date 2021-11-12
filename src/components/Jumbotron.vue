<template>
     <div id="jumbotron">
          <div class="container">
               <div>
                    <a href="">CURRENT SERIES</a>
               </div>
          </div>
     </div>
</template>

<script>


export default{
    
}
</script>

<style scoped lang="scss"> 

#jumbotron{
     background-image: url("../assets/img/jumbotron.jpg");
     background-size: cover;
     background-repeat: no-repeat;
     height: 40vh;
     position: relative;

     &>div{
          position: absolute;
          bottom: -2.5%;
          left:15%;
     }
}

a{
     font-size: 1.7rem;
     font-weight: 600;
     background-color: #0282f9;
     color: white;
     padding: 10px 30px 10px 30px; 
}



</style>
