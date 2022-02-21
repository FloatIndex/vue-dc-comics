<template>
    <footer>
        <section class="footer-top">
            <!-- continer -->
            <div class="container">

                <!-- prima colonna -->
                <div class="col">
                    <ul>
                        <h3 class="ul-title">dc comics</h3>
                        <li>
                            <a href="#">Characters</a>
                        </li>
                        <li>
                            <a href="#">Comics</a>
                        </li>
                        <li>
                            <a href="#">Movies</a>
                        </li>
                        <li>
                            <a href="#">TV</a>
                        </li>
                        <li>
                            <a href="#">Games</a>
                        </li>
                        <li>
                            <a href="#">Videos</a>
                        </li>
                        <li>
                            <a href="#">News</a>
                        </li>
                    </ul>

                    <ul>
                        <h3 class="ul-title">shop</h3>
                        <li>
                            <a href="#">Shop DC</a>
                        </li>
                        <li>
                            <a href="#">Shop DC Collectibles</a>
                        </li>
                    </ul>
                </div>
                <!-- fine prima colonna -->
                
                <!-- seconda colonna -->
                <div class="col">
                    <ul>
                        <h3 class="ul-title">dc</h3>
                        <li>
                            <a href="#">Terms Of Use</a>
                        </li>
                        <li>
                            <a href="#">Privacy policy (New)</a>
                        </li>
                        <li>
                            <a href="#">Ad Choices</a>
                        </li>
                        <li>
                            <a href="#">Advertising</a>
                        </li>
                        <li>
                            <a href="#">Subscriptions</a>
                        </li>
                        <li>
                            <a href="#">Talent Workshops</a>
                        </li>
                        <li>
                            <a href="#">CPSC Certificates</a>
                        </li>
                        <li>
                            <a href="#">Ratings</a>
                        </li>
                        <li>
                            <a href="#">Shop Help</a>
                        </li>
                        <li>
                            <a href="#">Contact Us</a>
                        </li>
                    </ul>
                </div>
                <!-- fine seconda colonna -->

                <!-- terza colonna -->
                <div class="col">
                    <ul>
                        <h3 class="ul-title">sites</h3>
                        <li>
                            <a href="#">DC</a>
                        </li>
                        <li>
                            <a href="#">MAD Magazine</a>
                        </li>
                        <li>
                            <a href="#">DC Kids</a>
                        </li>
                        <li>
                            <a href="#">DC Universe</a>
                        </li>
                        <li>
                            <a href="#">DC Power Visa</a>
                        </li>
                    </ul>
                </div>
                <!-- fine terza colonna -->

                <img src="../assets/img/dc-logo-bg.png" alt="dc logo">

            </div>
            <!-- fine container -->
        </section>

        <MyFooterBottom/>
    </footer>
</template>


<script>
import MyFooterBottom from './MyFooterBottom.vue'
export default{
    name: 'MyFooterTop',
    components: {
        MyFooterBottom
    }
}
</script>


<style scoped lang="scss">
@import "../assets/style/variables.scss";

.footer-top {
    height: 350px;
    background-image: url('../assets/img/footer-bg.jpg');
    background-size: cover;
    color: #fff;
    overflow: hidden;
    padding-top: 15px;

    .container {
        position: relative;
        display: flex;

        .col {
            margin-left: 30px;

            h3 {
                text-transform: uppercase;
                margin: 10px 0px;
            }

            a {
                color: $secondaryColor;
                font-size: 0.9rem;

                &:hover {
                    color: #fff;
                }
            }
        }

        img {
            position: absolute;
            top: -100px;
            right: 0;
        }
    }

}
</style>