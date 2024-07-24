<script setup>

    function msg(){
        alert('Trabalhando com eventos clique!');
    }
   

</script>



<template>

    <button @click="msg()">Clique aqui</button>
    
</template>