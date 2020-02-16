<template>
  <div class="home-wrapper">
    <div class="home">
      <HeadText />
      <MediaResource />
      <ButtonThree />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import MediaResource from "@/components/MediaResource.vue";
import ButtonThree from "@/components/ButtonThree.vue";
import HeadText from "@/components/HeaderText.vue";

export default {
  name: "Home",
  components: {
    MediaResource,
    ButtonThree,
    HeadText
  }
};
</script>

<style lang="scss">
@import "~@/assets/scss/variables.scss";

.home {
  max-width: 1460px;
  margin: auto;
  padding: 25px 35px 35px;

  &-wrapper {
    @media screen and (max-width: 700px) {
      background: $blue;
    }
  }

  @media screen and(max-width: 500px) {
    padding: 15px 10px 20px;
  }
}
</style>
