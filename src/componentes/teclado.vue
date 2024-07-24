<script setup>

    function msg(){
        alert('Executando função');
    }
   

</script>



<template>

    <input type="text" @keyup.enter="msg()">
    
</template>