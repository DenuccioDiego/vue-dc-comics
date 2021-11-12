<template>
     <div id="section_1">
          <div class="container d-flex">
               <Cards />
          </div>    
     </div>
</template>

<script>
import Cards from "./Cards.vue"

export default {
     components:{
          Cards,
     }
}
</script>

<style scoped lang="scss">

#section_1{
     background-color: #1c1c1c;
     width: 100%;
     height: 11rem;
     font-weight: 800;
     font-size: 2rem;
     color: white;
     display: flex;
     align-items: center;
}

</style>