<template>
  <v-app>
    <Toolbar/>
    <div id="app">
      <div id="nav">
        <router-link to="/">Home</router-link>
        <router-link to="/about">About</router-link>
      </div>
      <router-link>Home</router-link>
      <router-view></router-view>
      </div>
  </v-app>
</template>
<script>
import Toolbar from './components/Toolbar.vue'

export default {
  components: {
    Toolbar,
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
