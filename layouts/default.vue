<template>
  <div class="container">
    <AppHeader />
    <nuxt />
  </div>
</template>

<script>

</script>

<style>

.home-page {
  padding: 50px 30px;
}
h2 {
  margin-bottom: 30px;
  text-align: center;
}
.articles {
  margin: 0 auto;
  max-width: 800px;
}
.article {
  margin-bottom: 15px;
}
.article-inner {
  padding: 15px;
  background: #FFF;
  box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1);
  border-radius: 8px;
  display: flex;
}
.article-inner img {
  display: block;
  width: 100%;
  max-width: 300px;
}
.article-inner .detail {
  padding-left: 15px;
  padding-right: 15px;
}
h3 {
  color: #212121;
  font-size: 24px;
  text-decoration: none;
}
p {
  color: #888;
  font-size: 18px;
  text-decoration: none;
}

</style>
