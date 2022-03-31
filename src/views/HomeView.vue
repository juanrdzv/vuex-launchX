<template>
  <div class="home">

    <contador/>
    <cuadrado/>
    <botones/>


  </div>
</template>

<script>
import contador from "../components/contador.vue";
import cuadrado from "../components/cuadrado.vue";
import botones from "../components/botones.vue";


export default {
  name: 'HomeView',
  components: {
    contador,
    cuadrado,
    botones,
  }
}
</script>

<style>
body {
  margin: 0;
}

div{
  margin-bottom: 10px;
}

.counter{
  font-size: 80px;
}

.buttons button{
  font-size: 20px;
  width: 80px;
  margin: 0 10px;
  border-radius: 10px;
}

.cuadrado{
  font-size: 25px;
}

</style>
