<template>
  <div class="text-adn-photo">
    <img alt="Vue logo" src="../assets/viceo.png" />
    <div class="all-text">
      <p>Charidy Academy welcomes you to our most recent series</p>
      <p>of localized community engagement events entitled</p>
      <p>"Charidy Learning Series". Join us for CLS 2020 in Miami, NY</p>
      <p>and Montreal for an engaging learning event where you will</p>
      <p>network and learn along side nonprofit leaders,</p>
      <p>creative thinkers, financial experts and fundraising</p>
      <p>professionals.</p>
    </div>
  </div>
</template>

// <script>
// export default {
//   name: "ButtonThree",
//   props: {
//     msg: String
//   }
// };
//
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.all-text {
  width: 551px;
  height: 398px;
  margin-bottom: 181px;
  margin-left: 101px;
  margin-top: 109px;
}
.text-adn-photo {
  justify-content: flex-end;
  margin-top: 109px;
  display: flex;
  flex-flow: row wrap;
  width: 100%;
}

h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.all-text {
  justify-content: flex-end;
}
p {
  font-family: "VitoExtended";

  margin-top: 18px;
  margin-bottom: 18px;
  color: #67697a;
}
</style>
