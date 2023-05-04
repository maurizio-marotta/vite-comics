
<script>
export default {
  name: 'footer'
}
</script>

<template>
  <div class="root-3">
    <div class="barra-link">
      <ul class="primo">
        <li><img src="../assets/img/buy-comics-digital-comics.png" alt="" width="42" height="42"> Digital comics</li>
        <li><img src="../assets/img/buy-comics-merchandise.png" alt=""> Dc merch</li>
        <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""> Subscription</li>
        <li><img src="../assets/img/buy-comics-shop-locator.png" alt=""> Comic shop location</li>
        <li><img src="../assets/img/buy-dc-power-visa.svg" alt="">Dc power visa</li>
      </ul>
    </div>
    <div class="barra-link-2">
      <ul class="seconda">
        <li>charaters</li>
        <li>comics</li>
        <li>movies</li>
        <li>tv</li>
        <li>games</li>
        <li>collectibles</li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
  .root-3{
    display: flex;
    flex-direction: column;
    background-image: url(../assets/img/footer-bg.jpg);
    height: 60vh;
  }
  .barra-link{
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #0282F9;
  }

img{
  width: 40px; 
  height: 45px;
}
  ul.primo{
    margin: 10px;
  display: flex;
}

ul.primo li{
  color: white;
  list-style: none;
  margin: 10px;
}

ul.primo li:hover{
  color: blue;
  cursor: pointer;
}
ul.seconda{
  color: white;
}
.barra-link-2{
  height: 100%;
  padding: 0 150px;
  background-image: url(../assets/img/dc-logo-bg.png);
  background-repeat: no-repeat;
  background-position: right;
}
</style>