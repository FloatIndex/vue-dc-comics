<template>
    <header>
        <nav class="container">
            
            <a class="logo" href="#">
                <img src="../assets/img/dc-logo.png" alt="logo">
            </a>

            <ul>
                <li>
                    <a href="#">characters</a>
                </li>
                <li>
                    <a href="#">comics</a>
                </li>
                <li>
                    <a href="#">movies</a>
                </li>
                <li>
                    <a href="#">tv</a>
                </li>
                <li>
                    <a href="#">games</a>
                </li>
                <li>
                    <a href="#">collectibles</a>
                </li>
                <li>
                    <a href="#">videos</a>
                </li>
                <li>
                    <a href="#">fans</a>
                </li>
                <li>
                    <a href="#">news</a>
                </li>
                <li>
                    <a href="#">shop</a>
                </li>
            </ul>
            
        </nav>
    </header>
</template>


<script>
export default{
    name: 'MyHeader'
}
</script>


<style scoped lang="scss">
@import "../assets/style/variables.scss";

nav {
    height: 90px;
    display: flex;
    justify-content: space-between;
    align-items: center;

    a.logo {
        display: block;
        width: 60px;
        height: 60px;
        border-radius: 50%;
        overflow: hidden;
        flex-shrink: 0;

        img {
            width: 100%;
        }
    }

    ul {
        max-width: 80%;
        text-align: center;

        li {
            display: inline-block;
            padding: 0px 20px;
            line-height: 86px;

            a {
                text-transform: uppercase;
                font-size: 0.9rem;
                font-weight: bold;
                display: inline-block;
                border-bottom: 4px solid transparent;

                &:hover {
                    border-color: $primaryColor;
                    color: $primaryColor;
                }
            }
        }
    }
}
</style>