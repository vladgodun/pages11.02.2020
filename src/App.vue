<template>
  <div id="app">
    <router-view />
  </div>
</template>
<script>
import Home from "@/views/Home.vue";

export default {
  name: "Home",
  components: {
    Home
  }
};
</script>
<style lang="scss">
#app {
  color: #2c3e50;
  max-width: 1460px;
  margin: auto;
  min-height: 450px;
  height: auto;
}

@media screen and(max-width: 1024px) {
  #app {
    background-color: #0f6f93;
  }
  h1 {
    flex-direction: row wrap;
  }
  img {
    flex-direction: row wrap;
    max-width: 320px;
    height: 224px;
    margin: auto;
  }
  .all-text {
    flex-direction: row wrap;
    width: 359px;
    justify-content: flex-start;
    margin-left: 55px;
    margin-right: 50px;
    margin-top: 42px;
  }

  .text-adn-photo {
    margin-top: 53px;
    display: block;
  }

  p {
    margin: auto;
  }
  .head-npc {
    margin-left: 100px;
  }
  .nyc {
    margin-bottom: 41px;
  }
  .miami {
    margin-bottom: 41px;
  }
  .montreal {
    margin-bottom: 99px;
  }
}
</style>

