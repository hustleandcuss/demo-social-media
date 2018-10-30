<template>
  <div id="post">
    <img src="assets/logo.png"/>
    <p><span id="username">{{ username }}</span> {{ msg }}</p>
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
#username {
  font-weight: bolder;
}
body {
    background-color: lightblue;
}
</style>
