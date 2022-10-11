<template>
    <div id="mi-componente">
        <h1>Mi componente</h1>
        <h2>{{subtitulo}}</h2>
    </div>
</template>

<script>
export default {
    name: 'miComponente', 
    data() {
        return {
            subtitulo: 'Soy el subtitulo'
        }
    }
}

</script>