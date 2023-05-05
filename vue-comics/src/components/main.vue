
<script>
import card from './card.vue';
export default {
  name: 'main', 
  components: {
    card
  }
}

</script>

<template>
  <div class="">
    <div class="img"></div>


    <div class="root-2">
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
      <card series="series"/>
    </div>
    
  </div>
</template>

<style scoped>

.img{
  background-size: cover;
  height: 40vh;
  background-image: url(../assets/img/jumbotron.jpg);
}
.root-2{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100px;
  background-color: #1C1C1C;
}
h1{
  color: white;
}
</style>