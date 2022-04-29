<template>
    <div class="container">
       <div class="titolo">
            Want to work with us? Send us <span>a message</span>   
        </div> 
        <div class="testo">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt cupiditate quo, totam porro voluptate tempore 
            soluta blanditiis iste assumenda rem at? Eaque molestiae omnis reiciendis nihil necessitatibus, natus quaerat rem!
        </div>
        <button>
            CONTACT
        </button>
    </div>
</template>
<script>
    export default {
    name: 'PartnershipComp',    
  }
</script>
<style scoped lang="scss">
    .container{
        // width: 80%;
        height: 42vh;
        background-image: url('../assets/img/h-2-blog-img-1.jpg');
        background-size: cover;
        margin: 0px auto;
        text-align: center;

        .titolo{
            font-size: 60px;
            padding-top: 100px;

            span{
                font-style: italic;
                font-weight: 600;
            }
        }

        .testo{
            width: 70%;
            margin: 40px auto;
        }
    }
</style>
