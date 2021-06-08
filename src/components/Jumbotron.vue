<template>
  <div class="jumbotron">
      <div class="current">
          <p>Current Series</p>
      </div>
  </div>
</template>

<script>
export default {
    name: "Jumbotron"
}

</script>

<style lang="scss" scoped >
    .jumbotron {
        position: relative;
        height: 400px;
        width: 100%;
        background-image: url('../assets/img/jumbotron.jpg');
        background-position: initial; 
        background-size: cover;

        p {
            position: absolute;
            bottom: 0;
            left: 20%; 
            transform: translate(-50%, 45%);
            display: inline-block;
            padding: 20px;
            text-transform: uppercase;
            font-size: 25px;
            font-weight: bold;
            color: white;
            background-color: #0282f9;
        }
    }
</style>