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
                    <h2>Title</h2>
                    <ul>
                        <li><a href="#">link</a></li>
                    </ul>

                    <h2>Title</h2>
                    <ul>
                        <li><a href="#">linkmolto lungoooooooooooooooooooo</a></li>
                    </ul>
                </div>

                <div class="item">
                    <h2>Title</h2>
                    <ul>
                        <li><a href="#">linklunghissimooo</a></li>
                    </ul>
                </div>

                <div class="item">
                    <h2>Title</h2>
                    <ul>
                        <li><a href="#">link</a></li>
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
    background-size: 300px, cover;
    background-position-x: right 20%, 0;
    background-position-y: center;

    .box {
        display: flex;
        margin-left: 20%;

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

            h2 {
                text-transform: uppercase;
            }
        }

    }
}

</style>