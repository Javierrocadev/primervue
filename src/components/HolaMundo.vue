<template>
    <div>
        <h1>Mi primera app vue</h1>
        <h2>su nombre es : {{nombre}}</h2>
        <img src="./../assets/galaxy.jpg">
    </div>
</template>
<script>
    //siempre debemos exportar el nombre que deseemos 
    //dar al component en nuestra apicacion vue
    export default{
        name:"HolaMundo",
        data(){
            return {
                nombre:"alumno",
                numero :12,
                miarray:[],
                objeto:{}
            }
        }
    }
</script>
<style>
    h1{
        color:rgb(38, 93, 165)
    }
    @import './../assets/css/estilos.css'
</style>