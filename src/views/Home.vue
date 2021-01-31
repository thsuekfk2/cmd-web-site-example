<template>
  
  <div>
<h1>This is Home page</h1>
<hyebin title="home title"/>

  </div>
</template>

<script>
import hyebin from '@/components/Hyebin.vue';

export default {
  components : {
    hyebin
  },
  data(){
    return{
      name: "hyebin"
    }
  }
}
</script>

<style scoped>
h1{
  color: red;
}
</style>