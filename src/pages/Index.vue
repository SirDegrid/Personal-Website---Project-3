<template>
  <Layout>

    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <!-- <g-image alt="maggie profile" src="~/images/maggie_head.jpg" width="135" /> -->
    <img src="https://i.imgur.com/a3kMeZM.jpg" image alt="profile picture" width="170"/>
    <h1>Hello, world!</h1>

    <p>
      Lorem ipsum dolor sit amet, consectetur adipisicing elit. Pariatur excepturi labore tempore expedita, et iste tenetur suscipit explicabo! Dolores, aperiam non officia eos quod asperiores
    </p>

    <p class="home-links">
      <a href="https://www.linkedin.com/in/maggie-cameron-877b82106/?originalSubdomain=uk" target="_blank" rel="noopener">LinkedIn</a>
      <a href="https://github.com/SirDegrid" target="_blank" rel="noopener">GitHub</a>
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

body {
  background-color: lightblue;
}
</style>
