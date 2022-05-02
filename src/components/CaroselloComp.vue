<template>
    <div class="a">
        <div class=" freccia frecciaSx">
            F
        </div>
        <div class="container">
            
            <!-- TESTO del carosello -->
            <div class="testo">
                <!-- TITOLO -->
                <p class="titolo">
                    Devotion that never <span>ends</span>
                </p>
                <!-- DESCRIZIONE -->
                <p class="descrizione">
                    Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consecutor, adipisci velit, seq quia numquam eius modi.
                </p>
                <!-- BOTTONE -->
                <button>
                    READ MORE
                </button>    
            </div>
            <!-- IMMAGINI carosello -->
            <div class="img">
                <div class="img1"></div>
                <div class="img2"></div>
            </div>   
            
        </div>  
        <div class="freccia frecciaDx">
            F
        </div>  
    </div>
    
</template>

<script>

    export default {
        name: 'CaroselloComp',
    }
    
</script>

<style scoped lang="scss">

    .a{
        display: flex;
    }
    .container{
        display: flex;        
        width: 80%;
        margin: 80px auto;           
        height: 50vh;     
    }
    .testo{
        width: 30%;                     
        
        .titolo{
            font-size: 80px;                       

            span{
                font-style: italic;
                font-weight: bolder;
            }
        }
        .descrizione{
            margin: 60px 0;
            color: grey;
        }
               
    }
    .img{        
        height: 100%;
        display: flex;
        width: 70%;
        
        .img1{            
            width: 50%;
            background-image: url("../assets/img/h-2-slider-img-15.png");
            background-repeat: no-repeat;
            background-position: center;
            background-size: contain;
            margin-right: -110px;
            margin-left:150px ;
        }
        .img2{            
            width: 50%;
            background-image: url("../assets/img/h-2-slider-img-16.png");
            background-repeat: no-repeat;
            background-position: center;
            background-size: contain;
            margin-left:-110px ;
        }
    }
    .freccia{
        margin: auto 60px;
    }
</style>