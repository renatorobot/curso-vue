<script setup>

    let nome = 'Andrade Silva';
    let idade = '20';
    let num1 = 10;
    let num2 = 5;

</script>

<template>
    <p>{{ 'Olá, ' + nome + ' vc tem ' + idade + ' anos '}}</p>
    <p>{{ num1+num2 }}</p>
</template>