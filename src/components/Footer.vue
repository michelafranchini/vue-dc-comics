<template>
  <div id="app">
    <footer>
        <div class="container">
            <div class="footer_left">
                <h3>dc comics</h3>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
            </div>
        </div>
    </footer>
  </div>
</template>

<script>

export default {
  name: 'Footer',
}
</script>

<style lang="scss" scoped>
    .container {
        width: 70%;
        height: 150px;
        margin: auto;

        li {
            list-style: none; 
        }
        h3 {
            text-transform: uppercase;
        }
    }

</style>