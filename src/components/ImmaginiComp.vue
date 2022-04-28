<template>
  <div>
      <div class="container">
          <div class="containerImmagine">
            <img src="../assets/img/h-2-port-img-1.jpg" alt="">    
          </div>
          <div class="containerImmagine">
            <img src="../assets/img/h-2-port-img-2.jpg" alt="">    
          </div>
          <div class="containerImmagine">
            <img src="../assets/img/h-2-port-img-3.jpg" alt="">    
          </div>         
      </div>
      <div class="container">
          <div class="containerImmagine">
            <img src="../assets/img/h-2-port-img-4.jpg" alt="">    
          </div>
          <div class="containerImmagine">
            <img src="../assets/img/h-2-port-img-5.jpg" alt="">    
          </div>
          <div class="containerImmagine">
            <img src="../assets/img/h-2-port-img-6.jpg" alt="">    
          </div>         
      </div>
  </div>
</template>

<script>

    export default {
        name: 'ImmaginiComp',
    }
    
</script>

<style scoped lang="scss">
    .container{
        display: flex;          

        .containerImmagine{
            width: calc(100% / 3);                                  

            img{
                max-width: 100%;                
            }
        }
    }
</style>