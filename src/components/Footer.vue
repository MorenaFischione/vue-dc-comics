<template>
    <div class="container-footer">
        <footer>
            <nav class="nav-footer">
                <div class="menu-left">
                    <h3>DC COMICS</h3>
                    <ul>
                        <li> 
                            <a href="#">Character</a> 
                        </li>
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
                            <a href="#">Videos</a> 
                        </li>
                        <li> 
                            <a href="#">News</a> 
                        </li>
                    </ul>
                    <h3>SHOP</h3>
                    <ul>
                        <li> 
                            <a href="#">Shop DC</a> 
                        </li>
                        <li> 
                            <a href="#">Shop DC Collectibles</a> 
                        </li>
                    </ul>
                </div>
                <div class="menu-center">
                    <h3>DC</h3>
                    <ul>
                        <li> 
                            <a href="#">Terms of News</a> 
                        </li>
                        <li> 
                            <a href="#">Privacy policy (New)</a> 
                        </li>
                        <li> 
                            <a href="#">Ad Choices</a> 
                        </li>
                        <li> 
                            <a href="#">Advertising</a> 
                        </li>
                        <li> 
                            <a href="#">Jobs</a> 
                        </li>
                        <li> 
                            <a href="#">Subscriptions</a> 
                        </li>
                        <li> 
                            <a href="#">Talent WorksShops</a> 
                        </li>
                        <li> 
                            <a href="#">CPSC Certificates</a> 
                        </li>
                        <li> 
                            <a href="#">Ratings</a> 
                        </li>
                        <li> 
                            <a href="#">Contact Us</a> 
                        </li>
                    </ul>
                </div>
                <div class="menu-center">
                    <h3>SITES</h3>
                    <ul>
                        <li> 
                            <a href="#">DC</a> 
                        </li>
                        <li> 
                            <a href="#">MAD Magazine</a> 
                        </li>
                        <li> 
                            <a href="#">DC Kids</a> 
                        </li>
                        <li> 
                            <a href="#">DC Universe </a> 
                        </li>
                        <li> 
                            <a href="#">DC Power Visa</a> 
                        </li>
                    </ul>
                </div>
            </nav>
            <img class="logo-bg" src="../assets/img/dc-logo-bg.png" alt="sfondo con logo DC">
            
            
        </footer>
        <div  class="sign-up">
            <button>Sign-up now!</button>

        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    @import "../style/variables.scss";

    .container-footer {
        background-image: url(../assets/img/footer-bg.jpg);
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
    }

    footer {

        display: flex;
        justify-content: space-between;
        width: 70%;
        margin: 0 auto;
        position: relative;

        .nav-footer {
            display: flex;
            justify-content: start;

            ul{
            list-style-type: none;
            }



            li a {
                text-decoration: none;
                color: $colorLightGray;
                font-family: $fontMenu;
                line-height: 2rem;
                
            }

            .menu-left,
            .menu-center,
            .menu-right {
                padding: 20px 20px 20px 0px;
            }

            h3 {
                margin-bottom: 20px;
                color: $secondaryColor;
            }

            .logo-bg {
                position: absolute;
                left: 800px;
            }
        }
        
    }
    .sign-up {
        height: 100px;
        background-color: black;
        position: absolute;
        width: 100%;
        bottom: 1px;
    }
</style>