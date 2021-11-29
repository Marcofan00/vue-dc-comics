<template>
    <div class="product">
        <img :src="details.thumb" alt="">
        <h3>{{details.series}}</h3>

    </div>
</template>

<script>
export default {
    name: 'Mycomic',
    props: {
        details: Object
    }
}
</script>

<style scoped lang="scss">
    .product{
        img{
            width:160px;
            height: 170px;
            padding: 10px;
        }
        h3{
            padding:0 8px;
            text-transform: uppercase;
            max-width: 150px;
            text-align: left;
        }
    }
</style>