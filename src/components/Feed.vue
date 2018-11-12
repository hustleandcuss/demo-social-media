<template>
  <div id="feed">
    <Post imageName="1" username="zaralarsson" msg="And a bipedi bopedi booo and OFF you go to prom"/>
    <Post imageName="2" username="zaralarsson" msg="My side eye says “oh, so you’re not wearing Balmain? sorry, can’t relate” amazing show yesterday!"/>
    <Post imageName="3" username="zaralarsson" msg="Paris recap minus the beautiful shows"/>
    <Post imageName="4" username="zaralarsson" msg="Just a bean on film by @robinboee, who’s going to LA in 2 days to wrap my single up with a nice video. Vewy exciting"/>
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
