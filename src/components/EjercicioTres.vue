<template>
    <div>
        <input type="text" v-model="styleH2.color">
        <h2 v-bind:style="styleH2">Este es un texto estático</h2>
    </div>
</template>

<script>
    export default {
        data(){
            return {
                styleH2: {
                    color: "blue",
                },
            };
    },
};
</script>
