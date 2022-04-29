<template>
    <div class="container">
        <div class="column">            
            <div class="img">
                <div class="data">
                    <div class="giorno">07</div>
                    <div class="meseAnno">May '19</div>
                </div>
                <img src="../assets/img/h-2-blog-img-1.jpg" alt="">
            </div>
            <div class="testo">
                This way, loves: a detailed guide through new design
            </div>
            <div class="autore">
                By Emily Fields
            </div>
        </div>
        <div class="column">
            <div class="img">
                <div class="data">
                    <div class="giorno">07</div>
                    <div class="meseAnno">May '19</div>
                </div>
                <img src="../assets/img/h-2-blog-img-2.jpg" alt="">
            </div>
            <div class="testo">
                I try to give people a different way of looking art
            </div>
            <div class="autore">
                By Emily Fields
            </div>
        </div>
        <div class="column">
            <div class="img">
                <div class="data">
                    <div class="giorno">07</div>
                    <div class="meseAnno">May '19</div>
                </div>
                <img src="../assets/img/h-2-blog-img-3.jpg" alt="">
            </div>
            <div class="testo">
                Introduce Richard Lapier of those amazing features
            </div>
            <div class="autore">
                By Emily Fields
            </div>
        </div>
    </div>
</template>
<script>
    export default {
    name: 'ArticlesComp',    
  }
</script>
<style scoped lang="scss">
    .container{
        width: 80%;
        margin: 80px auto;
        display: flex;        
        
        .column{
            width: calc(100% / 3);
            padding: 10px;   
            
            .data{
                position: absolute;
                z-index: 1000;                
                background-color: #c0e1cf;
                border-radius: 200px;
                padding: 20px;
                margin: -30px 0 0 20px;
                text-align: center;
                .giorno{
                    font-size: 35px;
                }                
            }

            img{
                max-width: 100%;
                position: relative;
            }

            .testo{                
                font-size: 30px;
                margin: 35px auto 15px auto;                
            }

            .autore{
                font-size: 15px;
                font-style: italic;
            }
        }
    }
</style>
