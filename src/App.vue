<template>
  <nav>
    <router-link to="/">Earth</router-link> |
    <router-link to="/modal">Modal</router-link> |
    <router-link to="/template">Template</router-link> |
    <router-link to="/colorModal">Color Modal</router-link> |
    <router-link to="/heatmapView">Heat Map</router-link> |
  </nav>
  <router-view />
</template>


<script>
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
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
