<template lang="">
  <div>
      <TestComp />
      <br>
      <Exercise202 />
      <br>
      <Exercise203 />
      <br>
      <Exercise204 />

  </div>
</template>
<script>
import TestComp from './components/TestComp.vue'
import Exercise202 from './components/Exercise2-02.vue'
import Exercise203 from './components/Exercise2-03.vue'
import Exercise204 from './components/Exercise2-04.vue'
  export default{
    components: {
      TestComp,
      Exercise202,
      Exercise203,
      Exercise204

    }

  }

</script>