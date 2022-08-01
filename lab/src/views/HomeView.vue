<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <ComponentPrueba texto="pepito"/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue';
import ComponentPrueba from '@/components/ComponentPrueba.vue';

export default {
  name: 'HomeView',
  components: {
    // HelloWorld,
    ComponentPrueba
  }
}
</script>
