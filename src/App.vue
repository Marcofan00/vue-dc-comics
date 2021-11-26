<template>
  <div id="app">
    <Mynav/>
    <main>
    <Myjumbotron/>
    </main>
    <Myshop/>
    <Myfooter/>
    <Mysocial/>
  </div>
</template>

<script>
import Mynav from './components/Mynav.vue';
import Myjumbotron from './components/Myjumbotron.vue';
import Myshop from './components/Myshop.vue';
import Myfooter from './components/Myfooter.vue';
import Mysocial from './components/Mysocial.vue';
export default {
  name: 'App',
  components: {
    Mynav,
    Myjumbotron,
    Myshop,
    Myfooter,
    Mysocial,
  }
}
</script>

<style lang="scss">
.container {
  width: 70%;
  margin: 0 auto;
}
 ul {
	list-style: none;
}
</style>