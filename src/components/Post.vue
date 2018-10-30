<template>
  <div id="post">
    <img src="assets/logo.png"/>
    <h2>{{ username }}</h2>
    <h3>{{ msg }}</h3>
  </div>
</template>

<script>
export default {
  name: 'Post',
  props: {
    imageUrl: String,
    username: String,
    msg: String
  }
}
</script>

<style>
body {
    background-color: lightblue;
}
</style>
