<script>

export default {
  name:'Card',
  props:{
    thumb: String,
    price: String,
    series: String,
    type: String
  }
}
</script>
<template>

      <div
        class="card al-item-cent">
        <img :src="thumb ">
        <span>{{ name }}</span>
        class="card al-item-cent">
        <img :src="thumb ">
        <span>{{ name }}</span>
        class="card al-item-cent">
        <img :src=" thumb">
        <span>{{ name }}</span>
        class="card al-item-cent">
        <img :src=" thumb">
        <span>{{ name }}</span>
        class="card al-item-cent">
        <img :src="thumb">
        <span>{{ name }}</span>
        class="card al-item-cent">
        <img :src="thumb ">
        <span>{{ name }}</span>
      </div>


</template>


<style lang="scss" scoped>
    .card{
      width: calc(100% / 6);
      margin-top: 2.5rem;
      padding: 0 10px;
      img{
          width: 100%;
          aspect-ratio: 2 / 3;
          margin-bottom: .4rem;
      }
    }
  
  h2{
    color: white;
  }
</style>