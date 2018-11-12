<template>
  <div id="app">
    <Header/>
    <Feed/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Feed from './components/Feed.vue'

export default {
  name: 'app',
  components: {
    Header,
    Feed
  }
}
</script>

<style>
body, html {
  margin: 0;
  padding: 0;
  background-color: #edfff3;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
