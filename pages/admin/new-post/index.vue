<template>
  <div class="admin-new-post-page">
    <section class="new-post-form">
      <AdminPostForm/>
    </section>
  </div>
</template>

<script>
// import
import AdminPostForm from '@/components/Admin/AdminPostForm'

export default {
  components: {
    AdminPostForm
  }
}
</script>
