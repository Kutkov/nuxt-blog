<template>
  <section class="post-list">
    <PostPreview 
      id="1"
      thumbnail="https://icdn.lenta.ru/images/2018/09/21/15/20180921152446974/pic_dff6499e5b87f34e7a8e4bcb50f8fb10.jpg"
      title="Hello there"
      previewText="This my hello"
    />
    <PostPreview 
      id="2"
      thumbnail="http://www.vsemirnyjbank.org/content/dam/photos/780x439/2017/jun-1/ru-city-780.jpg"
      title="Hello there2"
      previewText="This my hello3"
    />
    <PostPreview 
      id="3"
      thumbnail="https://forbes.kz/img/articles/99661f12e332c908c2a3a754d3f4942b-big.jpg"
      title="Hello there3"
      previewText="This my hello3"
    />
  </section>
</template>

<script>
import PostPreview from '@/components/Posts/PostPreview'
export default {
  components: {
    PostPreview
  }
}
</script>

<style scoped>
  .posts-list {
    display: flex;
    padding: 20px;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
  }
</style>

