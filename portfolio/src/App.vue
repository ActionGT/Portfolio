<template>
  <div id="app">

    <router-view/>  
  </div>
  <nav>
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
  </nav>
  
</template>

<style lang="scss">
#app {
  font-size: 16px;
    color: #333;
    background-color: #fff;
    letter-spacing: 1px;
}

nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
