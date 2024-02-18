<script>
</script>

<template>
  <div class="contenedor">
    <img alt="Vue logo" src="./assets/logo.svg">
    <h1>Hola mundo desde VUE</h1>

    <br>

    <!-- Contador -->
    <h2>Contador: </h2>
    <button>Aumentar </button>
    <button>Disminuir</button>
    <button>Reiniciar</button>
  </div>
</template>

<style>
.contenedor {
  text-align: center;
  margin-top: 50px;
}

h1 {
  color: #42b983;
}

h2 {
  color: #42b983;
}

img {
  width: 100px;
  height: 100px;
}

button {
  margin: 10px;
  padding: 10px;
  background-color: #42b983;
  color: white;
  border: none;
  border-radius: 5px;
}

button:hover {
  cursor: pointer;
}

button:active {
  background-color: #3a9e7d;
}

button:focus {
  outline: none;
}
</style>