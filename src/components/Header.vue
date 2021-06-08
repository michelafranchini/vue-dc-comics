<template>
  <header>
      <div class="container navbar">
          <img src="../assets/img/dc-logo.png" alt="Logo DC">
          <ul>
              <li v-for="(link, index) in links" :key="index">
                  <a :href="link.link"> {{link.text}}</a>
              </li>
          </ul>
      </div>

      <div>
        <Jumbotron />
      </div>
  </header>
</template>

<script>
import Jumbotron from '../components/Jumbotron.vue'; 

export default {
  name: 'Header',
  components: {
    Jumbotron
  },
  data () {
      return {
          links: [
            {
              text: "characters", 
              link: "link", 
              active: false
            }, 
            {
              text: "comics", 
              link: "link", 
              active: true
            }, 
            {
              text: "movies", 
              link: "link", 
              active: false
            }, 
            {
              text: "tv", 
              link: "link", 
              active: false
            }, 
            {
              text: "games", 
              link: "link", 
              active: false
            }, 
            {
              text: "collectibles", 
              link: "link", 
              active: false
            }, 
            {
              text: "videos", 
              link: "link", 
              active: false
            },
            {
              text: "fans", 
              link: "link", 
              active: false
            },
            {
              text: "news", 
              link: "link", 
              active: false
            },
            {
              text: "shop", 
              link: "link", 
              active: false
            },
          ]
        }
    }
}
</script>

<style lang="scss" scoped>
    .navbar {
        display: flex;
        align-items: center;
        height: 120px;
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

            a:hover {
                color: #0282f9; 
            }

        }

        img {
           width: 90px; 
        }
    }


</style>