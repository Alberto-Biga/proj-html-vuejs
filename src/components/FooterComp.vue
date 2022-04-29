<template>
  <div class="container">
    <div class="row">
        <div class="column">
            <div>
                <img src="../assets/img/logo-sidearea-1.png" alt="">
            </div>
            <div>
                Let's get creative
            </div>
        </div>
        <div class="column">
            <div>
                maree.qode@gmail.com
            </div>
            <div>
                +44645321789
            </div>
        </div>
        <div class="column">
            <div>
                Avenue d'Auderghem 10
            </div>
            <div>
                1040 Brussels, Belgium
            </div>
        </div>
        <div class="column">
            <div>
                Stay in touch with us
            </div>
            <div>
                ""INSERIRE ICONE SOCIAL""
            </div>
        </div>
    </div>
  </div>
</template>

<script>
  

  export default {
    name: 'FooterComp',    
  }
</script>

<style scoped lang="scss">
  .container{
    background-color: #c0e1cf;
    // height: 25vh;
    padding: 50px;

    .row{
        width: 80%;
        margin: 0 auto;
        display: flex;

        .column{
            width: calc(100% / 4);            
            text-align: center;            
        }
    }
  }
</style>