<template>
  <div id="feed">
    <Post imageUrl="../assets/1.jpg" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="../assets/2.jpg" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="../assets/3.jpg" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="../assets/4.jpg" username="Användarnamn" msg="Hej en dag tjoho"/>
    <Post imageUrl="../assets/5.jpg" username="Användarnamn" msg="Hej en dag tjoho"/>
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
#feed {
  text-align: center;
}
</style>
