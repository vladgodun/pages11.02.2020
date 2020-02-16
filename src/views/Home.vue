<template>
  <div class="home">
    <h1>Charidy Learning Series</h1>
    <MediaResource />
    <!-- <img alt="Vue logo" src="../assets/viceo.png" /> -->
    <HelloWorld msg />
    <ButtonThree />
  </div>
</template>

<script>
// @ is an alias to /src
import MediaResource from "@/components/MediaResource.vue";
import ButtonThree from "@/components/ButtonThree.vue";

export default {
  name: "Home",
  components: {
    MediaResource,
    ButtonThree
  }
};
</script>
<style lang="scss">
h1 {
  color: #414359;
  text-align: center;
  font-family: "Open Sans", Regular;
  font-size: 46px;
}
</style>

