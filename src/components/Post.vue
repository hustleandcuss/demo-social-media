<template>
  <div id="post">
    <img v-bind:src="imageUrl"/>
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
img {
  height: 50px;
  weight: 50px;
}
#username {
  font-weight: bolder;
}
body {
    background-color: MintCream;
}

#post {
    border-bottom: 2px solid silver;
    color: MidnightBlue ;
    border-bottom-style: ridge;
}
</style>
