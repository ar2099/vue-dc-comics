<template>
  <div>
      <section>
    <ul>
        <li><img src="/img/buy-comics-digital-comics.png" alt=""> <span>DIGITAL COMICS</span></li>
        <li><img src="/img/buy-comics-merchandise.png" alt=""> <span>MERCHANDISE</span></li>
        <li><img src="/img/buy-comics-subscriptions.png" alt=""> <span>SUBSCRIPTIONS</span></li>
        <li><img src="/img/buy-comics-shop-locator.png" alt=""> <span>COMIC SHOP LOCATOR</span></li>
        <li><img src="/img/buy-dc-power-visa.svg" alt=""> <span>DC POWER VISA</span></li>
    </ul>
    </section>
  </div>
</template>

<script>
export default {
  name: 'BlueFooter',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div {
    background-color: #0282F9;
    padding-top: 30px;
    padding-bottom: 30px;
}
li {
    display: inline-flex;
    align-items: center;
    color: white;
    margin: 25px;
    font-size: 0.8em;
}

img {
    margin-right: 15px;
    height: 50px;
}

section {
    width: 80%;
    margin: auto;
}
</style>
