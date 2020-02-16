<template>
  <div class="last-bu">
    <div class="head-npc">
      <button class="nyc">RSVP NYC</button>
      <button class="miami">RSVP MIAMI</button>
      <button class="montreal">RSVP MONTREAL</button>
    </div>
  </div>
</template>


<script>
export default {};
</script>

<style>
.head-npc {
  margin-top: 107px;
  margin-left: 224px;
  margin-top: 109px;
  display: flex;
  flex-flow: row wrap;
}
.nyc {
  background-color: #107598;
  border-radius: 50px;
  border: 2px solid #107598;
  height: 65px;
  width: 330px;
  color: white;
  font-size: 25px;
  margin-right: 66px;
  font-family: "VitoExtended", Bold;
}
.miami {
  background-color: #107598;
  border: 2px solid #107598;
  height: 65px;
  width: 326px;
  border-radius: 50px;
  color: white;
  font-size: 25px;
  margin-right: 62px;
  font-family: "VitoExtended", Bold;
}
.montreal {
  background-color: #107598;
  border: 2px solid #107598;
  height: 65px;
  width: 330px;
  border-radius: 50px;
  color: white;
  font-size: 25px;
  font-family: "VitoExtended", Bold;
  margin-right: 62px;
}

@media screen and(max-width:600px) {
  .head-npc {
    display: flex;
    margin-left: 100px;
    margin: auto;
  }
}
</style>