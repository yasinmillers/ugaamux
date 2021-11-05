<template>
    <div>
        <h3>Name:{shapeName}</h3>
        <ul>
            <li>Area:{area}</li>
             <li>Perimeter:{perimeter}</li>
        </ul>
    </div>
</template>
<script>
export default {
  name: 'Shape',
  data() { return {}; },
  props: {
    shapename: String,
    perimeter: Number,
    area: Number,
  },
};
</script>

<style>

</style>
