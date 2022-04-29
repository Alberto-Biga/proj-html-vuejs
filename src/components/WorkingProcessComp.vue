<template>
  <div class="container">
    <div class="titolo">
        Working <span>process</span>
    </div>
    <div class="workingProcess">
        <div class="column">
            <div class="img">
                <img src="../assets/img/bulb_icon-icons.com_74600.png" alt="">    
            </div>            
            <span>
                First there's an idea    
            </span> 
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing. 
            </p>
        </div>
        <div class="column">
            <div class="img">
                <img class="a" src="https://www.svgrepo.com/show/43575/message-in-a-speech-bubble.svg" alt="">    
            </div>            
            <span>
                Then we talk about    
            </span> 
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing. 
            </p>
        </div>
        <div class="column">
            <div class="img">
                <img class="a" src="https://cdn-icons-png.flaticon.com/512/20/20095.png?w=360" alt="">    
            </div>
            <span>
                And we think about    
            </span> 
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing. 
            </p>
        </div>
        <div class="column">
            <div class="img">
                <img src="https://previews.123rf.com/images/aalbedouin/aalbedouin1705/aalbedouin170501535/78146678-penna-simbolo-di-contorno-colorato-elemento-di-matita-isolato-qualit%C3%A0-premium-in-stile-alla-moda-.jpg" alt="">
            </div>
            <span>
                So we draw along    
            </span> 
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing. 
            </p>
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
        width: 90%;
        margin: 100px auto;
        text-align: center;

        .titolo{
            font-size: 60px;

            span{
                font-style: italic;
                font-weight: 600;
            }
        }

        .workingProcess{
            background-image: url('../assets/img/svg-3.svg');
            background-repeat: no-repeat;             
            background-size: 900px;
            background-position: 150px 40px;           
            width: 70%;
            height: 45vh;
            margin: 100px auto;
            display: flex;
            justify-content: space-between;

            .column{
                width: calc( (100% / 4) - 56px );
                margin: 0 7px;
                text-align: center;                

                .img{
                    margin-bottom: 20px;
                }

                img{
                    max-width: 100%;
                    max-height: 130px;
                    padding: 25px;
                    background-color: #faf7f1;
                    // background-color: red;
                    border-radius: 150px ;
                    // margin: 10px
                }

                span{
                    font-weight: 600;
                    font-size: 20px;
                }

                p{
                    color: grey;
                    margin-top: 20px;
                }
            }
        }
    }
   
</style>