<template>
  <div>
    <Topbar></Topbar>
    <div class="container">
      <Content></Content>
    </div>
    <Bottombar></BottomBar>
  </div>
</template>

<script>
import Topbar from './components/Topbar.vue';
import Content from './components/Content.vue';
import Bottombar from './components/Bottombar.vue';

export default {
  name: "App",
  components: {
    Topbar,
    Content,
    Bottombar,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.container{
  align-content: center;
  margin: auto;
}

.container-content{
  display: flex;
  align-content: center;
}

.container div{
  padding: 1%;
  margin: 2%;
  border: black 1px solid;
  border-radius: 1em;
}

html{
  background-color: antiquewhite;
}

</style>
