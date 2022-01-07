<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/favicon.png" width="135" />

    <h1>欢迎~</h1>

    <p>
     Gridsome 是一个由Vue 驱动的静态站点生成器，用于为任何headless CMS、本地文件或API 构建CDN 就绪的网站。
     <p>
     使用 Vue.js、webpack 和 Node.js 等现代工具构建网站。从 npm 获取热重载和访问任何包，并在您最喜欢的预处理器（如 Sass 或 Less）中编写 CSS，并带有自动前缀。
    </p>

    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">技术社区</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">站长博客</a>
    </p>

  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Hello, world!'
  }
}
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
