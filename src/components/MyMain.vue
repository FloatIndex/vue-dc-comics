<template>
    <main>
        <section id="content">
            <div class="container">
                <h3>Content goes here</h3>
            </div>
        </section>

        <section>
            <MyShopping/>
        </section>
    </main>
</template>


<script>
import MyShopping from './MyShopping.vue'

export default{
    name: 'MyMain',
    components: {
        MyShopping
    }
}
</script>


<style scoped lang="scss">
#content {
    height: 110px;
    line-height: 110px;
    background-color: #000;

    h3 {
        color: #fff;

        &::before {
            content: '--> ';
        }
        &::after {
            content: ' <--';
        }
    }
}
</style>