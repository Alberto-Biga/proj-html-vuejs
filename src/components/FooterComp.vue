<template>
    <div class="container">
        <div class="row">
            <div :key="index" v-for="(element, index) in colonna" class="column">
                <div>
                    {{element.testoSopra}}                    
                </div>
                <div class="testoSotto">
                    {{element.testoSotto}}
                </div>
            </div>
        </div>
    </div>
</template>

<script>
  

  export default {
    name: 'FooterComp',   
    data(){
        return{
            colonna:[
            {
                testoSopra: 'Maree',
                testoSotto: 'Let`s get creative'
            },    
            {
                testoSopra: 'maree.qode@gmail.com',
                testoSotto:'+44645321789'
            }, 
            {
                testoSopra:'Avenue d`Auderghem 10',
                testoSotto:'1040 Brussels, Belgium'
            },
            {
                testoSopra: 'Stay in touch with us',
                testoSotto: '""INSERIRE ICONE SOCIAL""'
            }           
            ]
        }
    } 
  }
</script>

<style scoped lang="scss">
  .container{
    background-color: #c0e1cf;    
    padding: 50px;

    .row{
        width: 80%;
        margin: 0 auto;
        display: flex;

        .column{
            width: calc(100% / 4);            
            text-align: center;  
            
            .testoSotto{
                margin-top: 10px;
            }
        }
    }
  }
</style>