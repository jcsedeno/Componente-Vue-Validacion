<template>
<div id="Questions" class="questionnaire">
    <p>¿Cuando te debes abrochar el cinturon?</p>
      <input type="radio" id="Q-One" value="Q-One" v-model="toggle" checked: true>
      <label for="Q-One" >Con el automovil detenido</label>
      <br>
      <input type="radio" id="Q-Two" value="Q-Two" v-model="picked">
      <label for="Q-Two">Cuando empiezo a moverme</label>
      <br>
      <input type="radio" id="Q-Three" value="Q-Three" v-model="picked">
      <label for="Q-Three">Cuando me acuerde esté el automovil en movimiento o detenido</label>
    <p>¿Cuando debes ajustar los espejos?</p>
      <input type="radio" id="Q-One" value="Q-One" v-model="toggle" checked: true>
      <label for="Q-One" >Con el automovil detenido</label>
      <br>
      <input type="radio" id="Q-Two" value="Q-Two" v-model="picked">
      <label for="Q-Two">Cuando empiezo a moverme</label>
      <br>
      <input type="radio" id="Q-Three" value="Q-Three" v-model="picked">
      <label for="Q-Three">Cuando me acuerde esté el automovil en movimiento o detenido</label>
</div>

</template>

<script>
export default {
  name: 'Formulario'
}
</script>

<style>
.questionnaire {
  border-radius: 2px;
  padding: 20px 30px;
  margin-top: 1em;
  margin-bottom: 40px;
  user-select:none;
  overflow-x: auto;
};
p {
  font-size: 20px;
}
</style>
