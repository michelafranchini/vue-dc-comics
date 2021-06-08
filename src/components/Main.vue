<template>
  <div class="main_content">
      <div class="container">
        <Comics />
      </div>
  </div>
</template>

<script>
import Comics from "../components/Comics.vue"
export default {
  name: 'Main',
  components: {
    Comics, 
  }
}
</script>

<style lang="scss" scoped>
@import "../style/variables";   
    .container {
        width: 70%;
        height: 100%;
        margin: auto;
        display: flex;
        align-items: center;
        z-index: 2;
    }

    .main_content {
      padding: 70px 0;
      background-color: $colorGrey;
    }

</style>