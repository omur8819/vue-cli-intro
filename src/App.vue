<template>
  <h1>Sistem Durumu : {{ status }}</h1>
</template>

<script>
  export default {
    data: function(){
      return{
        status: "Pasif",
      }
    }   
  }
</script>

<style>
  h1{
    color: blue;
  }
</style>
