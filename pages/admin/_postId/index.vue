<template>
  <div class="admin-post-page">
    <section class="update-form">
      <AdminPostForm :post="loadedPost" />
    </section>
  </div>
</template>

<script>
import AdminPostForm from '@/components/Admin/AdminPostForm'

export default {
  components: {
    AdminPostForm
  },
  data() {
    return {
      loadedPost: {
        author: 'Maximlian',
        title: 'My awesome Post',
        content: 'Super amazing, thanks for that!',
        thumbnailLink: 'https://icdn.lenta.ru/images/2018/09/21/15/20180921152446974/pic_dff6499e5b87f34e7a8e4bcb50f8fb10.jpg'
      }
    }
  }
}
</script>
