<script>
//Definiamo il nome del componente ed eventualmente i componenti che usa (nessuno)
export default {
    name: "AppTitle",
}
</script>

<!-- Quando si importa questo componente verrà visualizzato questo HTML al suo posto -->
<template>
    <h1 class="green">Vue and node special guest = <span class="red">Nice!</span></h1>
</template>

<!-- Lo stile da applicare in QUESTO componente è il seguente -->
<!-- In style.css abbiamo invece lo stile generico -->
<style scoped>
h1>span.red {
    color: red;
    text-decoration: underline red;
    cursor: pointer;
}

h1>span.red:hover {
    color: blue;
    text-decoration: underline blue;
}

h1.green {
    color: green;
}

h1.green:hover {
    color: blue;
}
</style>