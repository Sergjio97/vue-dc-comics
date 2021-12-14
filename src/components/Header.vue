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
        height: 200px;
        display: flex;
        justify-content: space-around;
        align-items: center; 
    }

    ul {
        display: flex;
        li {
            list-style: none;
            a {
                text-decoration: none;
                text-transform: uppercase;
                padding: 50px 15px;
                color: #464646;

                &.active, &:hover {
                    border-bottom: 4px solid $main-color;
                }
            }
        }
    }

</style>