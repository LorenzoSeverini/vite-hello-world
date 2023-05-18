<script>
//Definiamo l'oggetto che conterrà la lista dei componenti importati, che vogliamo usare
export default {
   name: "Jumbotron",
}
</script>

<template>
    <h3 class="Jumbo">JumboTron</h3>
</template>

<!-- Qui abbiamo eventuale stile del componente "App", che è il contenitore generale -->
<style scoped>
.Jumbo {
    color: red;
    text-decoration: underline red;
    cursor: pointer;
    font-size: 12.5rem;
}

.Jumbo:hover {
    color: blue;
    text-decoration: underline blue;
}
</style>