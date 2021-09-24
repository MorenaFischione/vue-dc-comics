<template>
  <div>
      <header>
        <a href="#" class="logo-header">
            <img src="../assets/img/dc-logo.png" alt="logo DC">
        </a>
        <nav>
            <ul>
                <li> 
                    <a href="#">Character</a> 
                </li>
                <li> 
                    <a href="#" class="active">Comics</a> 
                </li>
                <li> 
                    <a href="#">Movies</a> 
                </li>
                <li> 
                    <a href="#">Tv</a> 
                </li>
                <li> 
                    <a href="#">Games</a> 
                </li>
                <li> 
                    <a href="#">Collectibles</a> 
                </li>
                <li> 
                    <a href="#">Videos</a> 
                </li>
                <li> 
                    <a href="#">Fans</a> 
                </li>
                <li> 
                    <a href="#">News</a> 
                </li>
                <li> 
                    <a href="#">Shop</a> 
                </li>
            </ul>
        </nav>

      </header>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    @import "../style/variables.scss";

    header {
        display: flex;
        justify-content: space-evenly;

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
            font-family: $fontText;
            font-weight: 700;
            padding: 10px;
        }

        .active {
            color: $activeColor;
            border-bottom: 5px solid $activeColor;
        }
        


    }
    
</style>