<!-- Footer -->
<script>
    export default {
    name: 'Footer',
    }
</script>

<!-- Template -->
<template>
  <footer>
    <h3>Footer</h3>
    <ul>
      <li><a href="#">link 1</a></li>
      <li><a href="#">link 2</a></li>
      <li><a href="#">link 3</a></li>
      <li><a href="#">link 4</a></li>
    </ul>
  </footer>
</template>

<!-- Style -->
<style scoped>
footer {
  width: 100%;
  height: 10rem;
  display: flex;
  justify-content: center;
  align-items: center;
  border: dotted 1px #42b983;
}

footer h3 {
  font-size: 2rem;
  margin-right: 2rem;
  cursor: pointer;
  color: #42b983;
}

footer ul {
  display: flex;
  justify-content: center;
  align-items: center;
  list-style: none;
}

footer ul li {
  margin: 0 1rem;
}

footer ul li a {
  text-decoration: none;
  color: #8d2f09;
  font-size: 1.5rem;
}

footer ul li a:hover {
  color: #42b983;
  text-decoration: underline;
}
</style>