<template>
  <div class="hello">
    <h1>{{texto}}</h1>
    <a @click="myFuction" :href="link" target="_blank">Este es mi enlance</a>
    <input type="text" v-model="myInput" />
    <a href="#">Tu enlace {{myInput}}</a>
    </div>
</template>

<script>
export default {
  name: 'ComponentPrueba',
  props: {
    texto: String
  },
data(){
  return {
    link:"http://microsoft.com",
    myInput: "",
  };
}, 
methods: {
  myFuction(){
    alert('Has hecho click XD');
  },
},
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
