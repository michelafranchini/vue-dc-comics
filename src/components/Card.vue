<template>
  <div class="card">
      <img :src="item.thumb" :alt="item.series">
      <h2>{{item.series}}</h2>
  </div>
</template>

<script>
export default {
    name: 'Card', 
    props: ['item']
}
</script>

<style lang="scss" scoped> 
    .card {
        width: 200px;
        margin: 20px 0;

        img {
            object-fit: initial;
            display: block;
            cursor: pointer;
        }

        h2 {
            text-transform: uppercase;
            font-size: 17px;
            margin: 30px 0;
            color: white;
        }
    }
</style>