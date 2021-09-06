<template>

    <footer>
        <div class="footer-top">
            <div class="container">
                <div class="row space-around">
                    <div class="container-mini">
                    <div class="col">
                        <h4>DC COMICS</h4>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Video</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h4>DC</h4>
                        <ul>
                            <li><a href="#">Terms of Use</a></li>
                            <li><a href="#">Privacy Policy</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Adveristing</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h4>SITES</h4>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Vista</a></li>
                        </ul>
                    </div>
                </div>
                <div class="container-mini">
                    <figure>
                        <img src="@/assets/img/dc-logo-bg.png" alt="" srcset="">
                    </figure>
                </div>
                </div>
                
            </div>
        </div>
        <div class="footer-bottom z-1">
            <div class="container">
                <div class="row">
                    <div class="col">
                        <button type="button" id="btn-signup" class="btn-outline-b">Sign Up Now!</button>

                    </div>

                </div>
                    
            </div>
        </div>
    </footer>
    
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss" scoped>
    .footer-top{
        height: 400px;
        background-image: url('../assets/img/footer-bg.jpg');
        background-size: cover;
        background-repeat: no-repeat;
        color: #fff
    }
    .footer-bottom{
        height: 100px;
        display: flex;
        background: #303030;
        color: #fff;
    }
    .container-mini{
        max-width: 500px;
        display: flex;
        flex-direction: row;

    }
    .container-mini .col{
        margin-top: 20px;
        width: calc(100% / 3);
    }
    .col a{
        color: #fff;
    }
    .col h4{
        margin-bottom:10px;
    }
    .col ul li{
        list-style-type: none;
        margin-right: 10px;
    }
    .follow{
        display: inline;
    }
    .btn-outline-b{
        padding: 10px;
        border: 1px solid #0c7cec;
        background: transparent;
        color: #fff;
        cursor: pointer;
    }
    .btn-outline-b:hover{
        background-color: #12518d;
    }
</style>