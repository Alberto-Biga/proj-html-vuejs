<template>
  <header>
    <!-- SX [logo] -->
    <div>      
      <img src="../assets/img/logo-sidearea-1-1.png" alt="Immagine del logo"/>
    </div>
    <!-- DX [nav menu] -->
    <div>
      <ul>
        <li :key="index" v-for="(element,index) in vociUl">
          <a href="">{{element}}</a>
        </li>
        <li>
          <a href="">
            <img src="../assets/img/svg-1.svg" alt="">
          </a>
        </li>     
      </ul>
    </div>
  </header>
</template>

<script>
  export default {
    name: 'HeaderComp',
    props: {
      msg: String
    },
    data(){
      return{
        vociUl:[
          'HOME','PAGES','PORTFOLIO','BLOG','SHOP','ELEMENTS'
        ],
        // img:['../assets/img/logo-sidearea-1-1.png'],        
      }
    }
  }
</script>

<style scoped lang="scss">
  //flex a HEADER per creare parte SX [con logo] e parte DX [con NAV]
  header{
    display: flex;
    justify-content: space-between;    
    align-items: center;
    font-size: 20px;
    margin: 30px 30px;
  }
  //modifico UL e figli per renderla una NAV
  ul{
    list-style-type: none;
    display: flex;
    
    li{
      margin: 0 25px;

      a{
        text-decoration: none;
        font-weight: 600;
        color: black;
      }
    }
    
  }
</style>
