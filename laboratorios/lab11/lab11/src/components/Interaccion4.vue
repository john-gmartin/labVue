<script setup>
import {ref,reactive} from "vue";
let publicaciones=ref([
    { id:1,
      estiloBaile: "waacking",
      musica: "disco",
      descripción: "Waacking es un estilo de danza urbana nacido en los años 70. Se enfoca en movimientos rápidos de brazos y poses elegantes. Con ritmo, actitud y expresión, transmite fuerza, confianza y feminidad, creando una conexión emocional con la música."
    },
    { id:2,
      estiloBaile: "house",
      musica: "house",
      descripción: "La danza House es un estilo de baile urbano que surge en los años 80 en los clubes de Chicago y Nueva York. Se caracteriza por movimientos fluidos, footwork rápido y conexión con la música house, creando una atmósfera festiva y llena de energía."
    },
    { id:3,
      estiloBaile: "popping",
      musica: "funk y electro-funk",
      descripción: "El Popping es un estilo de danza urbana que se enfoca en la contracción y relajación muscular para crear movimientos rápidos y precisos. Se caracteriza por los hits, los aislamientos y la ilusión de movimientos robóticos, creando un estilo visualmente impactante y rítmicamente sincopado."

    }


    ])
</script>

<template>
  <div>
    <ul>
        <li v-for="publicacion in publicaciones" :key="publicacion.id">
            <h3>{{ publicacion.estiloBaile }}</h3> <br>
            <p>Se baila con {{ publicacion.musica }}.</p><br>
            <p>{{ publicacion.descripción }}</p>
        </li>
    </ul>
  </div>
</template>

<style scoped>

</style>