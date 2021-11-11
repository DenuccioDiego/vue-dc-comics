<template>
  
  <div class="container d-flex space-between" id="header">
    <div>
      <img  src="../assets/img/dc-logo.png" alt=""> 
    </div>
      
    <div class="d-flex">
      <li><a href="">CHARATERS</a></li>
      <li><a href="">COMICS</a></li>
      <li><a href="">MOVIES</a></li>
      <li><a href="">TV</a></li>
      <li><a href="">GAMES</a></li>
      <li><a href="">COLLECTIBLES</a></li>
      <li><a href="">VIDEOS </a></li>
      <li><a href="">FANS</a></li>
      <li><a href="">NEWS</a></li>
      <li><a href="">SHOP</a></li>
    </div> 
  </div>
    
    
</template>

<script>
export default {
  

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
#header{
height: 12vh;
font-weight: 600;
align-items: baseline;
margin-top: 1rem;

}

li{
  padding: 0 0.75rem 3.65rem 0.75rem;

  &:hover{
    border-bottom:3px solid #128af9 ;
  }
}

img{
  vertical-align: middle;
}

a:hover{
  color: #128af9;
}
</style>
