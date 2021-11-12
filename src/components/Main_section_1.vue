<template>
     <div id="section_1">
          <div class="container d-flex">
               <Cards />
               <div>
                    <a href="">LOAD MORE</a>
               </div>
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

     font-weight: 800;
     font-size: 2rem;
     color: white;
     display: flex;
     align-items: center;
}

a{
     color: white;
     background-color: blue;
     padding: 20px 50px 20px 50px;
     font-size: 0.70rem;
}

.d-flex div{
     margin-right: auto;
     margin-left: auto;
     padding: 50px 0 40px 0px;
}

</style>