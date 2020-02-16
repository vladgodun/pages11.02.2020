<template>
  <div class="media-wrapper">
    <img class="media-wrapper__img" alt="Man with microphone" src="~@/assets/viceo.png" />
    <p class="media-wrapper__text">
      Charidy Academy welcomes you to our most recent series
      of localized community engagement events entitled
      "Charidy Learning Series". Join us for CLS 2020 in Miami, NY
      and Montreal for an engaging learning event where you will
      network and learn along side nonprofit leaders,
      creative thinkers, financial experts and fundraising
      professionals.
    </p>
  </div>
</template>
<style scoped lang="scss">
@import "~@/assets/scss/variables.scss";

.media-wrapper {
  display: flex;
  justify-content: center;
  &__img {
    height: auto;
    width: 500px;
    margin-right: 7%;

    @media screen and (max-width: 900px) {
      margin-bottom: 45px;
    }

    @media screen and (max-width: 500px) {
      width: 100%;
    }
  }

  &__text {
    font-family: "VitoExtended";
    margin-bottom: 18px;
    color: $black_light;
    line-height: 1.5;
    margin-top: 23% auto 0;
    font-size: 20px;
    width: 37.5%;

    @media screen and(max-width: 900px) {
      width: 100%;
    }
  }

  @media screen and(max-width:900px) {
    flex-direction: column;
    align-items: center;
  }
}

// .all-text {
//   width: 551px;
//   margin-bottom: 181px;
//   margin-left: 101px;
//   margin-top: 109px;
// }
// font-family: "VitoExtended";
//   margin-top: 18px;
//   margin-bottom: 18px;
//   color: $black_light;
// .text-adn-photo {
//   justify-content: flex-end;
//   margin-top: 109px;
//   display: flex;
//   flex-flow: row wrap;
//   width: 100%;
// }

// p {
//
// }
</style>
