<script setup>

    let exibir = true;
    let media = 6.5;
   

</script>

<template>

    <h1 v-if="exibir">hello word</h1>

    <p v-if="media>=7">Aprovado(A)</p>
    <p v-else-if="media>=5">Em exame</p>
    <p v-else>Reprovado(A)</p>

</template>