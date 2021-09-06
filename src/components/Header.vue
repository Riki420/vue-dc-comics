<template>
    <header>
        <div class="header-top"></div>
        <div class="container">
            <div class="header-bottom">
                <figure>
                    <img src="../assets/img/dc-logo.png" alt="">
                </figure>
                <ul class="main-nav">
                    <li><a href="#">CHARACTERS</a></li>
                    <li><a href="#">MOVIES</a></li>
                    <li><a href="#">COMICS</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">GAMES</a></li>
                    <li><a href="#">COLLECTIONABLES</a></li>
                    <li><a href="#">VIDEOS</a></li>
                    <li><a href="#">FANS</a></li>
                    <li><a href="#">NEWS</a></li>
                    <li><a href="#">SHOP</a></li>
                </ul>
            </div>
        </div>
        
    </header>
</template>

<script>
export default {
    name: "Header"
}
</script>

<style lang="scss" scoped>
    header{
        border-bottom: 1px solid black;
    }
    .header-top{
     height: 20px;
     background-color: #000;   
    }
    .header-bottom{
        height: 120px;
        display: flex;

    }
    .main-nav{
        list-style-type: none;
        align-self: center;
        display: flex;

    }
    .main-nav li a{
        margin-right: 10px;
        justify-content: end;
        
    }
</style>