<template>
  <div class="main">
    <main>
        <h3> --&rsaquo; Content goes here &lsaquo;--</h3>
    </main>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped> 
    @import "../style/variables.scss";

.main {
    background-color: $bg-black;
}
main {
    width: 70%;
    margin: 0 auto;
    height: 500px;
    
    h3 {
        color: $secondaryColor;
        padding: 60px 0px;
        font-family: $fontText;
        font-weight: 700;
        font-size: 2rem;
    }

}
    

</style>