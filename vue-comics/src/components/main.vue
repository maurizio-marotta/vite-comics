
<script>
import seriesJson from '../data/dc-comics.json'
import card from './card.vue';
export default {
  name: 'main', 
  components: {
    card
  },
  data(){
    return{
      series: seriesJson
    }
  }
}
console.log(seriesJson);
</script>

<template>
    <div class="img"></div>
    <div class="root-2">
      <card v-for="(serie, index) in series" :series="serie.series" :thumb="serie.thumb" :key="index" />
    </div>
    
</template>

<style scoped>
.img{
  background-size: cover;
  height: 40vh;
  background-image: url(../assets/img/jumbotron.jpg);
}
.root-2{
  padding: 0px 100px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  width: 100%;
  background-color: #1C1C1C;
}
span{
  color: white;
}




</style>