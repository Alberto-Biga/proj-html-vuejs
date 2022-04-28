<template>
  <div class="container">
    <div class="titolo">
        Working <span>process</span>
    </div>
    <div class="workingProcess">
        <div class="column">
            <img src="" alt="">
            <span>
                First thre's an idea    
            </span> 
        </div>
        <div class="column">
            <span>
                Then we talk about    
            </span> 
        </div>
        <div class="column">
            <span>
                And we think about    
            </span> 
            
        </div>
        <div class="column">
            <span>
                So we draw along    
            </span> 
        </div>
    </div>
  </div>
</template>

<script>

    export default {
        name: 'WorkingProcessComp',
    }
    
</script>

<style scoped lang="scss">
    .container{
        width: 80%;
        margin: 100px auto;
        text-align: center;

        .titolo{
            font-size: 40px;

            span{
                font-style: italic;
                font-weight: 600;
            }
        }

        .workingProcess{
            background-image: url('../assets/img/svg-3.svg');
            background-repeat: no-repeat;
            background-size: contain;
            width: 80%;
            height: 45vh;
            margin: 100px auto;
            display: flex;
            justify-content: space-between;

            .column{
                width: calc( (100% / 4) - 80px );
                margin: 10px;
                text-align: center;
                border: 1px solid red;
            }
        }
    }
</style>