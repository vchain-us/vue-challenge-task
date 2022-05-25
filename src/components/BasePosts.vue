<template>
  <div class="posts">
    <h1>Posts</h1>
  </div>
</template>

<script>
export default {
  name: 'BasePosts',
  props: {
    posts: { type: Array, default: () => [] }
  }
}
</script>

<style lang="scss" scoped>
.posts {
  width: 600px;
  margin: 0 auto;
}
</style>
