<template>
  <div id="app">
    <TheHeader />
    <router-view/>
    <TheFooter />
  </div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheFooter from './components/TheFooter.vue'

export default {
  components: {
    TheHeader,
    TheFooter,
  }
}
</script>

<style lang="scss">
* {
  padding: 0;
  margin: 0;
}

body {
  background: #f1f1f1;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
