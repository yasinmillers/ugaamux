<template>
  <div>
   <h1>this home</h1>
    <Shape shapeName= "Triangle" perimeter = {2} area ={6}>/</Shape>
  </div>

</template>

<script>
// @ is an alias to /src
// import Shape from '@/components/HelloWorld.vue'
import Shape from '../components/Shape.vue';

export default {
  components: {
    Shape,

  },
};

</script>
