<template>
    <h2>Olá Mundo!, {{name}}</h2>
    <br>
    <input type="text" v-model="name">
</template>

<script>
    export default {
        data() {
            return {
                name: 'Teste'
            }
        }
    }
</script>
