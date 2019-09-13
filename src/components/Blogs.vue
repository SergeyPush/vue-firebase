<template>
  <div>
    <h2>Blogs</h2>
    <div v-for="(post, index) in posts" :key="index">{{ post.title }}</div>
  </div>
</template>

<script>
import axios from "axios";
export default {
  data() {
    return {
      posts: []
    };
  },

  created() {
    axios
      .get("https://jsonplaceholder.typicode.com/posts")
      .then(response => (this.posts = response.data));
  }
};
</script>

<style lang="scss" scoped>
</style>