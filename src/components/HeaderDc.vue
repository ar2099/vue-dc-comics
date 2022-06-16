<template>
  <div class="centrale">
    <nav>
    <img src="/img/dc-logo.png" alt="logo">
    <ul>
      <li>CHARACTERS</li>
      <li>COMICS</li>
      <li>MOVIE</li>
      <li>TV</li>
      <li>GAMES</li>
      <li>COLLECTIBLES</li>
      <li>VIDEO</li>
      <li>FANS</li>
      <li>NEWS</li>
      <li>SHOP</li>


    </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: 'HeaderDc',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.centrale {
 display: flex;
 justify-content: center;

}
li {
  display: inline-block;
  padding: 40px 15px 50px 15px;
  // margin: 0px 10px 0px 10px;
  font-weight: bold;
  color: rgb(64, 64, 64);
  border-top: 10px solid rgb(255, 255, 255);
  border-bottom: 10px solid rgb(255, 255, 255);
  background-color: rgb(255, 255, 255);
}

li:hover {
  display: inline-block;
   padding: 40px 15px 50px 15px;
  // margin: 0px 10px 0px 10px;
  font-weight: bold;
  color: rgb(19, 97, 244);
  border-top: 10px solid rgb(255, 255, 255);
  border-bottom: 10px solid rgb(19, 97, 244);
  background-color: rgb(255, 255, 255);
}

img {
  margin: 10px;
}

nav {
 display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 0px;
  width: 80%;
}
</style>
