<template>
  <div>
    <HeaderComp/>
    <CaroselloComp/>
  </div>
</template>

<script>
  import HeaderComp from './components/HeaderComp.vue'
  import CaroselloComp from './components/CaroselloComp.vue'

  export default {
    name: 'App',
    components: {
      HeaderComp,
      CaroselloComp
    }
  }
</script>

<style lang="scss">
  //reset
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
</style>
