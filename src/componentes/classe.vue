<script setup>

    let validacao = false;
   

</script>

<style>

    .ok{color: green;}
    .falha{color: red;}

</style>

<template>

<p :class="validacao? 'ok' : 'falha'">Utilizando diretiva class</p>
    
</template>