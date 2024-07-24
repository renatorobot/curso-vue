<script setup>

    function validar(){
        alert('formulario enviado');
    }


</script>



<template>

    <form @submit="validar">
        <input type="submit" value="Enviar Formulario">
    </form>
    
</template>