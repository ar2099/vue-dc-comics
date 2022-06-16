<template>
  <div  class="corpo">
    <p class="scritta">content goes there</p>
  </div>
</template>

<script>
export default {
  name: 'MainDc',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.corpo {
    background-color: rgb(32, 32, 32);
    min-height: 100px;
    margin: 0px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.scritta {
color: white;

}

</style>
