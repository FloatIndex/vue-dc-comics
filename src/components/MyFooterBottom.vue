<template>
    <section class="footer-bottom">
        <div class="container">
            <button>sign-up now</button>
            
            <ul>
                <li>
                    <a class="follow-us" href="#">follow us</a>
                </li>
                <li>
                    <a href="#"><i class="fa-brands fa-facebook"></i></a>
                </li>
                <li>
                    <a href="#"><i class="fa-brands fa-twitter"></i></a>
                </li>
                <li>
                    <a href="#"><i class="fa-brands fa-youtube"></i></a>
                </li>
                <li>
                    <a href="#"><i class="fa-brands fa-pinterest"></i></a>
                </li>
                <li>
                    <a href="#"><i class="fa-solid fa-location-dot"></i></a>
                </li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    name: "MyFooterBottom"
}
</script>


<style scoped lang="scss">
@import "../assets/style/variables.scss";

.footer-bottom {
    background-color: $grey;

    .container {
        height: 90px;
        display: flex;
        justify-content: space-between;
        align-items: center;

        button {
            padding: 10px;
            color: #fff;
            background-color: transparent;
            border: 1px solid $primaryColor;
            text-transform: uppercase;

            &:hover {
                cursor: pointer;
                color: $primaryColor;
            }
        }

        .follow-us {
            color: $primaryColor;
            text-transform: uppercase;
            font-weight: bold;

            &:hover {
                color: $secondaryColor;
            }
        }

        li {
            display: inline-block;
            color: $secondaryColor;
            margin-left: 30px;

            svg {
                transform: scale(1.5);

                &:hover {
                color: $primaryColor;
                }
            }
        }
        
    }
}
</style>