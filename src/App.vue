<template>
  <div id="app">
   
    <router-view/>
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  /* color: #2c3e50; */
}

#nav {
  padding: 30px;
}
.green-underline {
  width: 3vw;
  border-top: 4px solid #49a347;
}
.list-star{
    list-style-image: url('../public/star.png');
}

/* #nav a { */
  /* font-weight: bold; */
  /* color: #2c3e50; */
/* } */

/* #nav a.router-link-exact-active {
  color: #42b983;
} */
</style>
