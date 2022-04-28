<template>
  <header>
    <!-- SX [logo] -->
    <div>      
      <img src="../assets/img/logo-sidearea-1.png" alt="">
    </div>
    <!-- DX [nav menu] -->
    <div>
      <ul>
        <li>
          <a href="">HOME</a>
        </li>
        <li>
          <a href="">PAGES</a>
        </li>
        <li>
          <a href="">PORTFOLIO</a>
        </li>
        <li>
          <a href="">BLOG</a>
        </li>
        <li>
          <a href="">SHOP</a>
        </li>
        <li>
          <a href="">ELEMENTS</a>
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
