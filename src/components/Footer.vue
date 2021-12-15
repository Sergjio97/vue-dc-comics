<template>
    <footer>

        <!-- ***** SEZIONE SHOP ***** -->
        <section class="shop">
            <div class="icons">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="digital comics">
                <a href="#">dc comics</a>
            </div>

            <div class="icons">
                <img src="../assets/img/buy-comics-merchandise.png" alt="dc merchandise">
                <a href="#">dc merchandise</a>
            </div>

            <div class="icons">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
                <a href="#">subscriptions</a>
            </div>

            <div class="icons">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="comic shop locator">
                <a href="#">comic shop locator</a>
            </div>

            <div class="icons">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="dc power visa">
                <a href="#">dc power visa</a>
            </div>            
        </section>

        <!-- ***** SEZIONE INFO ***** -->
        <section class="info">
            <div class="box">
                <div class="item">
                    <h3>dc comics</h3>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#">Comics</a></li>
                        <li><a href="#">Movies</a></li>
                        <li><a href="#">Tv</a></li>
                        <li><a href="#">Games</a></li>
                        <li><a href="#">Videos</a></li>
                        <li><a href="#">News</a></li>
                    </ul>

                    <h3>shop</h3>
                    <ul>
                        <li><a href="#">Shop DC</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                    </ul>
                </div>

                <div class="item">
                    <h3>dc</h3>
                    <ul>
                        <li><a href="#">Terms Of Use</a></li>
                        <li><a href="#">Shop DC Collectibles</a></li>
                        <li><a href="#">Privacy policy (New)</a></li>
                        <li><a href="#">Ad Choices</a></li>
                        <li><a href="#">Advertising</a></li>
                        <li><a href="#">Jobs</a></li>
                        <li><a href="#">Subscriptions</a></li>
                        <li><a href="#">Talent Workshops</a></li>
                        <li><a href="#">CPSC Certificates</a></li>
                        <li><a href="#">Ratings</a></li>
                        <li><a href="#">Shop Help</a></li>
                        <li><a href="#">Contact Us</a></li>
                    </ul>
                </div>

                <div class="item">
                    <h3>Sites</h3>
                    <ul>
                        <li><a href="#">DC</a></li>
                        <li><a href="#">MAD Magazine</a></li>
                        <li><a href="#">DC kids</a></li>
                        <li><a href="#">DC Universe</a></li>
                        <li><a href="#">DC Power Visa</a></li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- ***** SEZIONE LOGIN ***** -->
        <section class="login"></section>

    </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';

// ***** SEZIONE SHOP *****
.shop {
    width: 100vw;
    background-color: $main-color;
    display: flex;
    justify-content: center;

    .icons {
        padding: 60px 0px;
        margin-right: 100px;
        cursor: pointer;
        display: flex;
        align-items: center;
    }

    img {
        width: 50px;
        margin-right: 15px;
    }

    a {
        text-transform: uppercase;
        text-decoration: none;
        color: #fff;
    }
}

// ***** SEZIONE INFO *****
.info {
    width: 100vw;
    background-image: url('../assets/img/dc-logo-bg.png'), url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: 500px, cover;
    background-position-x: right 20%, 0;
    background-position-y: center, top;

    .box {
        display: flex;
        margin-left: 20%;
        padding-bottom: 30px;

        .item {
            margin-right: 25px;
            padding: 40px 0px;

            ul {
                margin-bottom: 15px;
            }
            
            li {
                list-style: none;

                a {
                    text-decoration: none;
                    color: $footer-link;

                }

            }

            h3 {
                text-transform: uppercase;
                color: #fff;
                margin-bottom: 15px;
            }
        }

    }
}

</style>