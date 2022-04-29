<template>
  <div>
    <HeaderComp/>
    <CaroselloComp/>
    <ImmaginiComp/>
    <WorkingProcessComp/>
    <PartnershipComp/>
    <ArticlesComp/>
  </div>
</template>

<script>
  import HeaderComp from './components/HeaderComp.vue'
  import CaroselloComp from './components/CaroselloComp.vue'
  import ImmaginiComp from './components/ImmaginiComp.vue'
  import WorkingProcessComp from './components/WorkingProcessComp.vue'
  import PartnershipComp from './components/PartnershipComp.vue'
  import ArticlesComp from './components/ArticlesComp.vue'

  export default {
    name: 'App',
    components: {
      HeaderComp,
      CaroselloComp,
      ImmaginiComp,
      WorkingProcessComp,
      PartnershipComp,
      ArticlesComp
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
