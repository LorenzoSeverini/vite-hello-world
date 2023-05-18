<!-- immagine grande  -->
<template>
    <div class="big-img">
        <img src="https://picsum.photos/seed/picsum/200/300" alt="big-img" />
    </div>
</template>

<!-- Template -->
<script>
export default {
    name: 'BigImg',
}
</script>

<!-- Style -->
<style scoped>
.big-img {
    width: 100%;
    height: 31.25rem;
    display: flex;
    justify-content: center;
    align-items: center;
    border: dotted 1px #42b983;
}

.big-img img {
    width: 100%;
    height: 80%;
    display: flex;
    justify-content: center;
    align-items: center;
    overflow: hidden;
    cursor: pointer;
    padding: 2rem;
}
</style>