<template>
  <div id="app">
    <div>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/helloworld">HelloWorld</router-link></li>
        <li><router-link to="/formhelper">dynamics component</router-link></li>
      </ul>
    </div>
    <router-view>
    </router-view>
  </div>
</template>

<script>

export default {
  name: 'App',
  data() {
    return {

    }
  },
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
