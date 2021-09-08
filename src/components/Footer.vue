<template>
    <footer>
    <!--FOOTER TOP-->

        <div class="footer-top">
            <div class="container">
                <div class="row space-around">
                    <div class="container-mini">
                    <div class="col">
                        <h3>DC COMICS</h3>
                        <ul class="mt-2">
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Video</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h3 class="mt-2">SHOP</h3>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectiables</a></li>
                        </ul>
                    </div>
                    <div class="col">
                        <h3>DC</h3>
                        <ul class="mt-2">
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
                        <h3>SITES</h3>
                        <ul class="mt-2">
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
                        <img src="@/assets/img/dc-logo-bg.png" class="dc-foot" alt="logo-footer" >
                    </figure>
                </div>
                </div>
                
            </div>
        </div>
        <!--FOOTER BOTTOM-->
        <div class="footer-bottom z-1">
            <div class="container-foot">
                <div class="row">
                    <div class="col-foot">
                        <!--BOTTONE SIGN-UP-->
                        <button type="button" id="btn-signup" class="btn-outline-b">Sign-Up Now!</button>
                        <ul class="none-style d-inline">
                            <li>
                                <span class="follow">FOLLOW US:</span>
                            </li>
                            <li>
                                <a href="#"><img src="@/assets/img/footer-facebook.png" alt="Facebook-logo"></a> 
                            </li>
                            <li>
                                <a href="#"><img src="@/assets/img/footer-periscope.png" alt="Periscope-logo"></a> 
                            </li>
                            <li>
                                <a href="#"><img src="@/assets/img/footer-pinterest.png" alt="pinterest-logo"></a> 
                            </li>
                            <li>
                                <a href="#"><img src="@/assets/img/footer-twitter.png" alt="twitter-logo"></a> 
                            </li>
                            <li>
                                <a href="#"><img src="@/assets/img/footer-youtube.png" alt="youtube-logo"></a> 
                            </li>
                        </ul>
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
    @import "../assets/scss/vars.scss";
    
    /*CONTAINER E COL PER IL FOOTER*/
    .container-mini{
        min-width: 500px;
        display: flex;
        flex-direction: row;
            .col{
                margin-top: 20px;
                width: calc(100% / 3);
                    a{
                    color: #fff;
                    }
                    h4{
                    margin-bottom:10px;
                    }
                    
                    ul{
                        list-style-type: none;
                        li{
                            margin-right: 10px;
                            a{
                                &:hover{
                                    color: $dc-color;
                                }
                            }
                        }
                    }
        }
    }   
    .poisition-end{
        position: absolute;
        right: 0;
        top: 50px;
    }
    .dc-foot{
        position: absolute;
        right: 60px;
    }

    /*FOOTER BOTTOM*/
    .d-inline{
        li{
            margin-right: 10px;
            a{
                &:hover{
                    filter: invert(1);
                }
            }
        }
    }
    .col-foot{
        flex-grow: 1;
        display: flex;
        align-items: center;
        justify-content: space-between;
    }
    

    /*BUTTON OUTLINE*/
    .btn-outline-b{
        padding: 10px;
        border: 1px solid $dc-color;
        background: transparent;
        color: #fff;
        cursor: pointer;
            &:hover{
                background-color: $dc-color;
            }
    }
    .follow{
        vertical-align: 10px;
        color: $dc-color;
        font-size: 1.2em;
    }
    
</style>