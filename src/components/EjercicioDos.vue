<template>
    <div>
        <h1>Suma:</h1>
        <input type="number" v-model="primerNumero">
        <input type="number" v-model="segundoNumero">
        <button v-on:click="sumar">Sumar</button>
        <p>{{suma}}</p>
    </div>
</template>

<script>
    export default {
        data() {
            return {
                suma: 0
            };
        },
        methods: {
            sumar(){
                this.suma = parseInt(this.primerNumero) + parseInt(this.segundoNumero); 
            }
        }
    };
</script>

<style></style>