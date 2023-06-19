<script setup>
import NavBar from "./components/NavBar.vue"
import Footer from "./components/Footer.vue"
import Interaccion2 from "./components/Interaccion2.vue";
import Interaccion3 from "./components/Interaccion3.vue";
import Interaccion4 from "./components/Interaccion4.vue";
</script>

<template>
 <div>
  <div>
    <NavBar/>
  </div>
 
  <div>
    <Interaccion2/>
  </div>

  <br>
  <p>-----------------------------------------------------------------------------</p>
  <br>

  <div>
    <Interaccion3/>
  </div>

  <br>
  <p>-----------------------------------------------------------------------------</p>
  <br>

  <div>
    <Interaccion4/>
  </div>

  <div>
    <Footer/>
  </div>
 </div>
</template>

<style scoped>

</style>
