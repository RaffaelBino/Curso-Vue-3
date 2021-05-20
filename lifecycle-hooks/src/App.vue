<template>
  <h1>LifeCycle Hooks</h1>
</template>

<script>
import {onMounted} from 'vue'

export default {
 setup() {
   onMounted(() => {
     console.log('Foi montado com Composition API');
   })
 }
}
// export default {
//  mounted() {
//    console.log('Foi montado o Options API');
//  }
// }
</script>

<style>

</style>