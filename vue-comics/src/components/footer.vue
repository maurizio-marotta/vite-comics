
<script>
export default {
  name: 'footer'
}
</script>

<template>
  <div class="root-3">
    <div class="background">
      <ul>
        <li><img class="" src="../assets/img/buy-comics-digital-comics.png" alt="" width="42" height="42"> Digital comics</li>
        <li><img src="../assets/img/buy-comics-merchandise.png" alt=""> Dc merch</li>
        <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""> Subscription</li>
        <li><img src="../assets/img/buy-comics-shop-locator.png" alt=""> Comic shop location</li>
        <li><img src="../assets/img/buy-dc-power-visa.svg" alt="">Dc power visa</li>
      </ul>
    </div>
  </div>
</template>

<style scoped>
  .root-3{
    background-image: url(../assets/img/footer-bg.jpg);
    height: 60vh;
  }
  .background{
    display: flex;
    justify-content: center;
    align-items: center;
    height: 15vh;
    background-color: #0282F9;
  }

img{
  width: 40px; 
  height: 45px;
}
  ul{
  display: flex;
}

li{
  color: white;
  list-style: none;
  margin: 10px;
}

li:hover{
  color: blue;
  cursor: pointer;
}

</style>