<template>
  <div id="app">
    <header>
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="Logo DC">
            <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">Games</a></li>
            </ul>
        </div>
    </header>
  </div>
</template>

<script>

export default {
  name: 'Header',
}
</script>

<style lang="scss" scoped>
    header {
        display: flex;
        align-items: center;
        height: 120px;
        background-color: lightblue;
    }
    .container {
        width: 70%;
        height: 100%;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        ul {
            list-style: none;

            li {
                display: inline-block;
                padding: 10px;
            }
            a {
                text-decoration: none;
                text-transform: uppercase;
                color: #1c1c1c;
            }

        }

        img {
           width: 90px; 
        }
    }


</style>