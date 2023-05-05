<script>

export default {
  name:'Card',
  props:{
    thumb: String,
    series: String,
  },
}
</script>
<template>
    <div class="container">
      <div class="card">
        <img :src="thumb">
        <span>{{ series }}</span>
      </div>
    </div>

</template>


<style lang="scss" scoped>
.container{
  padding: 0px 150px;
}

.card{
  background-color: rgba(0, 255, 255, 0);
  float: left;
  width: calc(100% / 6);
  margin-top: 2.5rem;
  padding: 0 10px;
img{
  width: 100%;
  aspect-ratio: 2 / 3;
  margin-bottom: .4rem;
  }
}


span{
  color: white;
}
</style>