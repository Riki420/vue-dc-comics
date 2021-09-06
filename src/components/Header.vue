<template>
    <header>
        <div class="container">
            <div class="header-top"></div>
            <div class="header-bottom">
                <figure>
                    <img src="../assets/img/dc-logo.png" alt="">
                </figure>
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
</style>