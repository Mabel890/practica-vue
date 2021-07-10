<template>
    <div>
        <h1>Personas activas</h1>
        <ul>
            <li v-for="item in items" :key="item.nombre">
                <div v-if="item.activo">{{item.nombre}} {{item.apellido}}</div>
            </li>
        </ul>
    </div>
</template>

<script>
    export default {
        name: "people",
        data() {
            return {
                items: [
                    {
                        nombre:"Valentina",
                        apellido: "Isaza",
                        activo: false,
                    },
                    {
                        nombre:"David",
                        apellido: "Espinosa",
                        activo: true,
                    },
                    {
                        nombre:"Isabella",
                        apellido: "Posada",
                        activo: true,
                    },
                    {
                        nombre:"Mariana",
                        apellido: "Zapata",
                        activo: false,
                    },
                    {
                        nombre:"Camilo",
                        apellido: "Varón",
                        activo: true,
                    },
                    {
                        nombre:"Felipe",
                        apellido: "Álvarez",
                        activo: false,
                    },
                    {
                        nombre:"Angélica",
                        apellido: "Escobar",
                        activo: false,
                    },
                    {
                        nombre:"David",
                        apellido: "Botero",
                        activo: true,
                    },
                    {
                        nombre:"Mateo",
                        apellido: "Agudelo",
                        activo: false,
                    },
                    {
                        nombre:"Alejandro",
                        apellido: "Henao",
                        activo: true,
                    },
                ],
            };
        },
    };
</script>
