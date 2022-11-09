<template>
    <header>
        <h1>{{ messaggio }}</h1>
    </header>
</template>

<script>
export default {
    name: 'AppTitle',
    data() {
        return {
            messaggio: 'La mia prima app con Vite'
        }
    },
    methods: {

    }
}
</script>

<style lang="css" >
header {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100vw;
    height: 80px;
    padding: 20px;
    background-color: chocolate;
}
</style>