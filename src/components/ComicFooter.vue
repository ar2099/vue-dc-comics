<template>
  <div>
      <nav>
        <ul>
            <li class="titolo">DC COMICS</li>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
            <li class="titolo">SHOP</li>
            <li>Shop DC</li>
            <li>Shop DC Collectibles</li>
        </ul>
        <ul>
            <li class="titolo">DC</li>
            <li>Terms OF Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choices</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscriptions</li>

            <li>Talent Workshops</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shot Help</li>
            <li>Contact Us</li>
        </ul>
        <ul>
            <li class="titolo">SITES</li>
            <li>Dc</li>
            <li>Mad Magazine</li>
            <li>Dc kids</li>
            <li>Dc Universe</li>
            <li>Dc power-visa</li>
            
        </ul>
    </nav>

        <img src="/img/dc-logo-bg.png" alt="logo">
  </div>
</template>

<script>
export default {
  name: 'ComicFooter',
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
div {
    height: 330px;
    background-image: url("/public/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: space-around;
    color: grey;
}
nav {
    display: flex;
}
ul {
    margin-left: 16px;
}
img {
    height: 450px;
}

li {
    font-size: 0.9em;
    margin-top: 4px;
}

.titolo {
    font-size: 1.3em;
    color: white;
    font-weight: bold ;
    margin-bottom: 10px;
    margin-top: 10px;
}
</style>
