<template>
  <div id="post">
    <img :src="imagePath(imageName)" />
    <p><span id="username">{{ username }}</span> {{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: 'Post',
  props: {
    imageName: String,
    username: String,
    msg: String
  },
  methods: {
    imagePath(imageName) {
      return require("../assets/" + imageName + ".jpg");
    }
  },
}
</script>

<style scoped>
img {
  height: 250px;
  weight: 250px;
}

p {
  width: 500px;
  word-wrap: break-word;
  margin-left: auto;
  margin-right: auto;
}

#username {
  font-weight: bolder;
}

#post {
  width: 600px;
  margin-top: 2em;
  padding-top: 3em;
  color: MidnightBlue;
  border: 2px solid silver;
  border-bottom-style: ridge;
  margin-left: auto;
  margin-right: auto;
}
</style>
