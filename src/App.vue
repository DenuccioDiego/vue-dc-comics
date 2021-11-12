<template>
   
  <div id="app">
    
    <Header_ />
    <Jumbotron />
    <Main_section_1 />
    <Main_section_2 />
    <Footer_top />
    <Footer_bottom />

  </div>
  
</template>

<script>
import Header_ from "./components/Header_.vue"
import Jumbotron from "./components/Jumbotron.vue"
import Main_section_1 from "./components/Main_section_1.vue"
import Main_section_2 from "./components/Main_section_2.vue"
import Footer_top from "./components/Footer_top.vue"
import Footer_bottom from "./components/Footer_bottom.vue"

export default {
   
  components: {
    Header_,
    Jumbotron,
    Main_section_1,
    Main_section_2,
    Footer_top,
    Footer_bottom,
  }
}
</script>

<style lang="scss">

*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
  font-family: "Greta Sans Condensed Bold","Greta Sans Bold",Arial,sans-serif;
}

.container{
max-width: 1320px;
margin-right: auto;
margin-left: auto;
}

.d-flex{
  display: flex;
  flex-wrap: wrap;

}

.align-items-center{
  align-items: center;
}

.space-between{
  justify-content: space-between;
}

li{
  list-style: none;
}

a{
  text-decoration: none ;
  color: black;
}
</style>
