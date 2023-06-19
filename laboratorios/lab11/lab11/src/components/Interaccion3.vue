<script setup>

let valorBoleano= true
</script>

<template>
   <div>
    <p v-if="valorBoleano"> Este texto se muestra porque el valor boleano es "true"</p>
    <p v-else> No se muestra texto</p>
   </div>
</template>

<style scoped>

</style>
