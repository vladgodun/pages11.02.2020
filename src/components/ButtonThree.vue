<template>
  <div class="buttons-wrapper">
    <button class="buttons-wrapper__btn">rsvp nyc</button>
    <button class="buttons-wrapper__btn">rsvp miami</button>
    <button class="buttons-wrapper__btn">rsvp montreal</button>
  </div>
</template>



<style lang="scss">
@import "~@/assets/scss/variables.scss";

.buttons-wrapper {
  margin-top: 101px;
  display: flex;
  justify-content: center;
  flex-wrap: wrap;

  &__btn {
    background-color: $blue;
    border-radius: 50px;
    height: 65px;
    width: 330px;
    color: $white;
    font-size: 25px;
    font-family: "VitoExtended", Bold;
    border: none;
    text-transform: uppercase;

    &:nth-child(2) {
      margin: 0 65px;
    }

    @media screen and(max-width: 1200px) {
      &:last-child {
        margin-top: 65px;
      }
    }
    @media screen and(max-width: 875px) {
      border: 2px solid $blue;
      width: 100%;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
      &:last-child {
        margin-top: 40px;
      }

      &:nth-child(2) {
        margin: 40px 0 0;
      }
    }
  }

  @media screen and(max-width:600px) {
    margin-top: 50px;
  }
}
</style>