<template>
  <div class="container-side-bar">
    <h4>Here is an example of a sidebar component</h4>
    <p>The following is a procedurally generated list of items:</p>
    <ul id="array-rendering">
      <li v-for="item in items" :key="item.id">{{item.message}}</li>
    </ul>
  </div>
</template>

<style>
.container-side-bar {
  width: 25vw;
}
</style>

<script>
export default {
  data() {
    return {
      items: [
        { message: "item one", key: 1 },
        { message: "item two", key: 2 },
        { message: "item three", key: 3 },
        { message: "item three", key: 3 },
        { message: "item three", key: 3 },
      ],
    };
  },
};
</script>