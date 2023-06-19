<script setup>
import { ref, reactive } from "vue";
const suma= ref(2+2);

let BioInfo= reactive({
    nombre:"Jonatan",
    apellidos: "García Martín",
    edad: 28,
    población: "Barcelona"
})

const funcionBio=()=>{
    return `Hola! Mi nombre es ${BioInfo.nombre} ${BioInfo.apellidos}, tengo ${BioInfo.edad} años y vivo en ${BioInfo.población}.`
}

</script>

<template>
 <div>
   <div>
    <h2>Imprime resultado de una suma en HTML</h2>
    <p>El resultado es {{ suma }}</p>
   </div>
   <div>
    <h2>Imprime un string mediante una función</h2>
    <p>{{ funcionBio() }}</p>
   </div>
 </div>
</template>

<style scoped>

</style>
