<!-- Creare un secondo componente AppHero, che visualizza un jumbotron. -->
<script>
// definire il componente AppHero
export default {
    name: 'AppHero',
}
</script>

<!-- template -->
<template>
    <div class="jumbotron">
        <h1 class="display-4">Ciao Vite-Vue!</h1>
        <p class="lead">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab laborum facere voluptates quis saepe quas accusamus sint eos at eum</p>
        <hr class="my-4">
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Autem libero consequatur soluta saepe!</p>
        <a class="btn btn-primary btn-lg" href="#" role="button">Lorem</a>
    </div>
</template>

<!-- style -->
<style scoped>
.jumbotron {
    background-color: #4d296d;
    padding: 2rem;
    border-radius: 0.3rem;
    margin-bottom: 2rem;
}

.jumbotron h1 {
    font-size: 2.5rem;
    font-weight: 300;
    color: #d88417;
    cursor: pointer;
}

.jumbotron p {
    font-size: 1.25rem;
    font-weight: 300;
    color: #000000;
    cursor: pointer;
}

.jumbotron hr {
    margin-top: 1rem;
    margin-bottom: 1rem;
    border: 0;
    border-top: 3px solid rgba(226, 124, 124, 0.1);
}

.jumbotron .btn {
    font-size: 1.25rem;
    padding: 0.75rem 1.5rem;
    color: #252222;
    text-decoration: none;
    cursor: pointer;
}

.jumbotron .btn:hover {
    color: #252222;
    background-color: #42b983;
    border-color: #42b983;
}

.jumbotron .btn:focus {
    box-shadow: 0 0 0 0.2rem rgba(66, 185, 131, 0.5);
}

.jumbotron .btn + .btn {
    margin-left: 1rem;
}
</style>