<template>
  <div class="home-page">
    <section class="intro">
      <h1>Get the latest tech news!</h1>
    </section>
    <section class="featured-posts">
      <nuxt-link :to="'/posts/' + 1">
        <article class="post-preview">
          <div class="post-thumbnail" style="background-image: url('https://icdn.lenta.ru/images/2018/09/21/15/20180921152446974/pic_dff6499e5b87f34e7a8e4bcb50f8fb10.jpg');"></div>
          <div class="post-content">
            <h1>Post Title</h1>
            <p>Preview text</p>
          </div>
        </article>
      </nuxt-link>
      <nuxt-link :to="'/posts/' + 2">
        <article class="post-preview">
          <div class="post-thumbnail" style="background-image: url('https://kareliyanews.ru/wp-content/uploads/2018/08/neva-city.jpg');"></div>
          <div class="post-content">
            <h1>Post Title 2</h1>
            <p>Preview text 2</p>
          </div>
        </article>
      </nuxt-link>
    </section>
  </div>
</template>

<style scoped>
.intro h1{
  text-align: center;
}
  .post-preview {
    border: 1px solid #ccc;
    box-shadow: 0 2px 2px #ccc;
    background-color: white;
    width: 90%;
  }
  a {
    text-decoration: none;
    color: black;
  }
  @media (min-width: 850px) {
    .post-preview {
      width: 400px;
      margin: 10px auto;
      padding: 10px;
    }
  }
  .post-thumbnail {
    width: 100%;
    height: 200px;
    background-position: center;
    background-size: cover;
  }

</style>
