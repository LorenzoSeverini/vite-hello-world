<script>
// definire il componente AppTitle
export default {
    name: 'AppTitle',
}
</script>

<!-- Template -->
<template>
    <h1>La mia prima app con Vite!</h1>
</template>

<!-- Style -->
<style scoped>
h1 {
    color: #42b983;
    font-size: 3rem;
}

h1:hover {
    color: #b33838;
    cursor: pointer;
}

h1:active {
    transform: scale(0.8);
}
</style>