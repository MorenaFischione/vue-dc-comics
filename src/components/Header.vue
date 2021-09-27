<template>
  <div>
      <header>
        <a href="#" class="logo-header">
            <img src="../assets/img/dc-logo.png" alt="logo DC">
        </a>
        <nav>
            <ul>
                <li v-for="(link, index) in links" :key="index">
                    <a :class="{ active : link.current}" href="">{{link.text}}</a>
                </li>
            </ul>
        </nav>

      </header>
  </div>
</template>

<script>
export default {
    name: "Header",
    data: function () {
    return {
      links: [
          {
              text: "Home",
              url: "#home",
              current: false,
          },
          {
              text: "Comics",
              url: "#comics",
              current: true,
          },
          {
              text: "Movies",
              url: "#movies",
              current: false,
          },
          {
              text: "Tv",
              url: "#tv",
              current: false,
          },
          {
              text: "Home",
              url: "#home",
              current: false,
          },
          {
              text: "Games",
              url: "#games",
              current: false,
          },
          {
              text: "Collectibles",
              url: "#collectibles",
              current: false,
          },
          {
              text: "Video",
              url: "#video",
              current: false,
          },
          {
              text: "Fans",
              url: "#fans",
              current: false,
          },
          {
              text: "News",
              url: "#news",
              current: false,
          },
          {
              text: "Shop",
              url: "#shop",
              current: false,
          },
      ]
    }
  },

}
</script>

<style lang="scss" scoped>
    @import "../style/variables.scss";

    header {
        width: 70%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;

        nav {
            align-self: center;
        }

        .logo-header {
            padding: 20px 0px;
        }

        ul{
            display: flex;
            justify-content: space-evenly;
            text-decoration: none;
            list-style-type: none;
        }

        li {
            padding:10px;
            
        }

        li a {
            text-decoration: none;
            color: $primaryColor;
            text-transform: uppercase;
            font-family: $fontMenu;
            font-weight: 700;
            padding: 10px;
        }

        .active {
            color: $activeColor;
            border-bottom: 5px solid $activeColor;
        }
        


    }
    
</style>