<template>
  <div class="urna-teclado">
    <div class="urna-teclado-numerico">
      <div class="urna-teclado-numerico-linha">
        <button>1</button>
        <button>2</button>
        <button>3</button>
      </div>
      <div class="urna-teclado-numerico-linha">
        <button>4</button>
        <button>5</button>
        <button>6</button>
      </div>
      <div class="urna-teclado-numerico-linha">
        <button>7</button>
        <button>8</button>
        <button>9</button>
      </div>
      <div class="urna-teclado-numerico-linha">
        <button>0</button>
      </div>
    </div>
    <div class="urna-teclado-acoes"></div>
  </div>
</template>

<script>
export default {
  name: "TecladoView",
};
</script>

<style scoped>
.urna-teclado {
  width: 40%;
  height: 100%;
  background-color: var(--ballot-box-keyboard-color);
  border-radius: 5px;
  padding: 20px;
}

.urna-teclado-numerico {
  widows: 100%;
}

.urna-teclado-numerico-linha {
  display: flex;
  justify-content: space-around;
  margin-bottom: 20px;
}

.urna-teclado-numerico button {
  background-color: var(--ballot-box-keyboard-button-color);
  color: var(--light-text-color);
  font-size: 30px;
  border-radius: 5px;
  width: 80px;
  height: 50px;
}
</style>
