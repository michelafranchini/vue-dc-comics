<template>
  <div id="app">
    <main>
        <div class="container">
            <p>Content container</p>
        </div>
    </main>
  </div>
</template>

<script>

export default {
  name: 'Main',
}
</script>

<style lang="scss" scoped>
    main {
        background-color: #1c1c1c;
    }
    .container {
        width: 70%;
        height: 150px;
        margin: auto;
        display: flex;
        align-items: center;
        z-index: 2;

        p {
            font-size: 30px;
            color: white;
        }
    }

</style>