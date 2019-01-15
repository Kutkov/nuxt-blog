<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news!</h1>
    </section>
    <PostList />

  </div>
</template>

<script>
import PostList from '@/components/Posts/PostList'
export default {
  components: {
    PostList
  }
}
</script>


<style scoped>
.intro{
  background-image: url('~assets/images/background.jpg');
  background-position: center;
  background-size: cover;
  padding: 60px 0;
}
.intro h1{
  text-align: center;
  margin: 0;
  color: #fff;
  font-size: 2em;
  text-shadow: 1px 1px 2px black, 0 0 1px black;
}
  

</style>
