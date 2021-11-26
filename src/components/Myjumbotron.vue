<template>
    <header id="jumbo-container">
        <img src="../assets/img/jumbotron.jpg" alt="">
    </header>
</template>

<script>
export default {
  name: 'Myjumbotron',
 
}
</script>
<style scoped lang="scss">
    #jumbo-container {
        height: 40vh;
        object-fit: cover;
        overflow: hidden;
        
        img {
            width: 100%; 
        } 
    }
</style>