<template>
    <main>
        <MyJumbo/>

        <ComicsList/>

        <MyShopping/>
    </main>
</template>


<script>
import MyShopping from './MyShopping.vue'
import MyJumbo from './MyJumbo.vue'
import ComicsList from './ComicsList.vue'

export default{
    name: 'MyMain',
    components: {
        MyShopping,
        MyJumbo,
        ComicsList
    }
}
</script>


<style scoped lang="scss">

</style>