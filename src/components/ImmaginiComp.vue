<template>
  <div>
    <div class="container">
            <!-- <div class="containerImmagine"></div> -->

      <div class="containerImmagine">
        <div class="testo">
          <h2>Illustration of Novels</h2>
          <p>Illustration</p>
        </div>
        <img src="../assets/img/h-2-port-img-1.jpg" alt="">
      </div>
      <div class="containerImmagine">
        <div class="testo">
          <h2>Illustration of Novels</h2>
          <p>Illustration</p>
        </div>
        <img src="../assets/img/h-2-port-img-2.jpg" alt="">
      </div>
      <div class="containerImmagine">
        <div class="testo">
          <h2>Illustration of Novels</h2>
          <p>Illustration</p>
        </div>
        <img src="../assets/img/h-2-port-img-3.jpg" alt="">
      </div>
      <div class="containerImmagine">
        <div class="testo">
          <h2>Illustration of Novels</h2>
          <p>Illustration</p>
        </div>
        <img src="../assets/img/h-2-port-img-4.jpg" alt="">
      </div>
      <div class="containerImmagine">
        <div class="testo">
          <h2>Illustration of Novels</h2>
          <p>Illustration</p>
        </div>
        <img src="../assets/img/h-2-port-img-5.jpg" alt="">
      </div>
      <div class="containerImmagine">
        <div class="testo">
          <h2>Illustration of Novels</h2>
          <p>Illustration</p>
        </div>
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
        flex-wrap: wrap;

        .containerImmagine{
            flex-basis: calc(100% / 3);
            position: relative;

            img{
                max-width: 100%;
                z-index: 2;
            }

            .testo{
              position: absolute;
              z-index: -1;
              background-color: white;
              padding: 10px;
              margin: 400px 0 ; 
              
              h2{
                font-size: 40px;
              }

              p{
                font-style: italic;
              }
            }

          }
    }

        .containerImmagine:hover{
          .testo{
            z-index: 1;
            
          }
        }
</style>