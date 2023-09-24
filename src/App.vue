<script>
</script>

<template>
  <div id="aboutme" class="card">
    <img src="./assets/avatar.png" alt="avatar" id="avatar"/>
    <div id="text">
      <p class="whitecolor nickname">DankNil</p>
      <p class="whitecolor desc">Programmer, Musician(maybe)... iusearchbtw</p>
    </div>
  </div>
  <div id="main" class="card">
    <h1 class="whitecolor">Hi!</h1>
  </div>
</template>

<style scoped>
.card {
  box-shadow: 10px -10px 0px 0px #F6EFA6, 20px -20px 0px 0px #36382E;
  background: #36382E;
  padding: 50px;
}

#main {
  display: flex;
  place-content: flex-start;
  width: auto;
  margin-top: 50px;
}

#aboutme {
  display: flex;
  width: fit-content;
  horiz-align: center;
  vertical-align: center;
  place-content: center;
  margin: 100px 20px 20px;
}

#text {
  float: left;
  padding-top: 10px;
}

.whitecolor {
  color: aliceblue;
}

#avatar {
  float: left;
  height: 128px;
}
</style>
