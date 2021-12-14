<template>
    <header>
        <img src="../assets/img/dc-logo.png" alt="logo header">
        <ul>
            <li><a href="#">characters</a></li>
            <li><a href="#">comics</a></li>
            <li><a href="#">movies</a></li>
            <li><a href="#">tv</a></li>
            <li><a href="#">games</a></li>
            <li><a href="#">collectibles</a></li>
            <li><a href="#">videos</a></li>
            <li><a href="#">fans</a></li>
            <li><a href="#">news</a></li>
            <li><a href="#">shop</a></li>
        </ul>
    </header>
</template>

<script>
export default {
    name: 'Header'
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';

    header {
        width: 100vw;
        display: flex;
        justify-content: space-around; 
    }

    img {
        padding: 40px 0px;
    }

    ul {
        display: flex;
        align-items: center;
        padding: 40px 0px;

        li {
            list-style: none;

            a {
                text-decoration: none;
                text-transform: uppercase;
                font-weight: 600;
                color: #464646;
                padding: 80px 15px;

                &.active, &:hover {
                    border-bottom: 4px solid $main-color;
                }
            }
        }
    }

</style>