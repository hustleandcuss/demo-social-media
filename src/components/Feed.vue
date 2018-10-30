<template>
  <div id="feed">
    <Post imageUrl="assets/logo.png" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="assets/logo.png" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="assets/logo.png" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="assets/logo.png" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="assets/logo.png" username="Användarnamn" msg="Hej en dag tjoho"/>
  </div>
</template>

<script>
import Post from './Post.vue'

export default {
  name: 'Feed',
  components: {
    Post,
  }
}
</script>

<style scoped>
</style>
