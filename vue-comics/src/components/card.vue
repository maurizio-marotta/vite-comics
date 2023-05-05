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

      <div class="card">
        <img :src="thumb">
        <span>{{ series }}</span>
      </div>

</template>


<style lang="scss" scoped>
.container{
  padding: 0px 150px;
}

.card{
  display: flex;
  justify-content: center;
  align-items: center;
  background-color:#1C1C1C;
  float: left;
  width: calc(100% / 6);
  margin-top: 2.5rem;
  padding: 0 10px;
  border: 0px;
img{
  display: flex;
  justify-content: center;
  width: 50%;
  height: 50%;
  margin-bottom: .4rem;
  }
}


span{
  color: white;
}
</style>