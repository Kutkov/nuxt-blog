<template>
  <div class="single-post-page">
    <section class="post">
      <h1 class="post-title">Title of the Post</h1>
      <div class="post-details">
        <div>Last update on XXX</div>
        <div>Written by NAME</div>
      </div>
      <p class="post-content">Content of the post</p>
    </section>
    <section class="post-feedback">
      <p>Let me know what you think about the post, send a mail to <a href="mailto:feedback@mail.ru">feedback@mail.ru</a></p>
    </section>
  </div>
</template>

<style scoped>
  .single-post-page {
    padding: 30px;
    text-align: center;
    box-sizing: border-box;
  }
  .post {
    width: 100%;
  }
  @media (min-width: 765px) {
    .post {
      width: 600px;
      margin: auto;
    }
    .post-title {
      margin: 0;
    }
    .post-details {
      padding: 10px;
      border-bottom: 3px solid #ccc;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
    }
    @media (min-width: 768px) {
      .post-details {
        flex-direction: row;
      }
    }
  }
</style>
