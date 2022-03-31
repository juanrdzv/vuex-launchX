<template>
    <nav>
      <router-link to="/" class="linksNav">Inicio</router-link> |
      <router-link to="/about" class="linksNav">Informacion</router-link>
    </nav>

  <router-view/>
</template>

<style>
nav {
    background-color: #c76c30;
    width: 100%;
    height: 100%;
    min-height: 100px;
    display: flex;
    justify-content: center;
    align-items: center;
  
}

nav a {
  font-weight: bold;
  color: #152053;
}

nav a.router-link-exact-active {
  color: #bebbe7;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
