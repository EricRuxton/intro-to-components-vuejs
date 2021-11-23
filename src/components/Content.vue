<template>
  <div>
    <h2>This is an example of a body made up of components</h2>
    This component in particlular is an example of what an article might look
    like on a website<br />
    <article class="container-content">
      <p>
      <Article></Article>
      <Article></Article>
      <Article></Article>
      <Article></Article>
      </p>
      <Sidebar></Sidebar>
    </article>
  </div>
</template>

<script>
import Article from "./Article.vue";
import Sidebar from "./Sidebar.vue";

export default {
  components: {
    Sidebar,
    Article,
  },
};
</script>

<style>

</style>
