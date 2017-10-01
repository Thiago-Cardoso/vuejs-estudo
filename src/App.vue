<template>
<div>
     <h1>{{ titulo }}</h1>
     <ul>
       <li v-for="foto of fotos">
          <img :src="foto.url" :alt="foto.title">
        </li>
     </ul>
</div>
</template>

<script>
export default {
  data(){

      return  {
        titulo: 'Alurapic',
        fotos: [
          {
           url: 'http://tudosobrecachorros.com.br/wp-content/uploads/cachorro-independente.jpg',
           titulo: 'Cachorro'
          },
           {
           url: 'http://tudosobrecachorros.com.br/wp-content/uploads/cachorro-independente.jpg',
           titulo: 'Cachorro'
          }
        ]
      }

  }
}
</script>

<style>

</style>
