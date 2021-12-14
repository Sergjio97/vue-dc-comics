<template>
    <footer>
        
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

        <section class="info"></section>
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

.shop {
    width: 100vw;
    background-color: $main-color;
    display: flex;
    justify-content: center;

    .icons {
        padding: 40px 0px;
        margin-right: 120px;
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

</style>