<template>
    <section id="shopping">
        <div class="container">
            <ul>
                <li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="buy digital comics">
                        digital comics
                    </a>
                </li><li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="buy dc merchandise">
                        dc merchandise
                    </a>
                </li><li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="subscription">
                        subscription
                    </a>
                </li><li>
                    <a href="#">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="comic shop locator">
                        comic shop locator
                    </a>
                </li><li>
                    <a href="#">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="power visa">
                        dc power visa
                    </a>
                </li>
            </ul>
        </div>
    </section>
</template>


<script>
export default{
    name: 'MyShopping'
}
</script>


<style scoped lang="scss">
@import "../assets/style/variables.scss";
#shopping {
    background-color: $primaryColor;
    color: #fff;

    .container {
        height: 120px;
        display: flex;
        justify-content: space-evenly;
        align-items: center;
        align-content: center;

        li {
            display: inline-block;

            a {
                text-transform: uppercase;
                padding: 10px 0px;
                margin: 0px 30px;

                &:hover {
                    color: $darkGrey;
                }

                img {
                    height: 40px;
                    max-width: 45px;
                    vertical-align: middle;
                    margin: 10px;
                }
            }
        }
    }
}
</style>