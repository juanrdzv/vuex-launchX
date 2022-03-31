<template>
    <div class="about">
    <p>El contenido de esta pagina es un contador con numeros aleatorios mediante un API</p>
    <p><a href="https://www.random.org/clients/http/api/">Link Random Api</a></p>
  </div>
  <footer>
    <div class="infoFooter">
      <p> Hecho por Juan Rodriguez V.</p>
      <p>Para Launch X By Microsoft</p>
    </div>
  </footer>
</template>

<style scoped>
*{
  width: 100%;
  margin: 0;
  padding: 0;
  
}
.about{
  width: 100%;
  height: 100%;
  min-height: 355px;
  padding-top: 400px;
}

footer{
  width: 100%;
  justify-self: end;
  height: 100%;
  min-height: 200px;
  display: flex;
  justify-content: center;
  padding: 5px;
  background-color: rgba(133, 131, 131, 0.514);
}

.infoFooter{
  display: flex;
  flex-direction: column;
  justify-content: center;
  width: 50%;
  align-items: center;

}





</style>
