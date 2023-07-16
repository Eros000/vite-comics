<script>

export default {
  data() {
    return {
      
    }
  },

  components: {
    
  },

  methods: {

  }
}
</script>

<template>

  <header>

    <div class="header-container">

      <div class="logo-container">
        <img src="../assets/dc-logo.png" alt="">
      </div>

      <div class="nav-container">
        
        <ul>

          <li>
            <a href="#">
              CHARACTERS
            </a>
          </li>

          <li class="active-page">
            <a href="#">
              COMICS
            </a>
          </li>

          <li>
            <a href="#">
              MOVIES
            </a>
          </li>

          <li>
            <a href="#">
              TV
            </a>
          </li>

          <li>
            <a href="#">
              GAMES
            </a>
          </li>

          <li>
            <a href="#">
              COLLECTIBLES
            </a>
          </li>

          <li>
            <a href="#">
              VIDEOS
            </a>
          </li>

          <li>
            <a href="#">
              FANS
            </a>
          </li>

          <li>
            <a href="#">
              NEWS
            </a>
          </li>

          <li>
            <a href="#">
              SHOP
            </a>
          </li>

        </ul>

      </div>

    </div>

     

  </header>
  
</template>

<style scoped lang="scss">

header{
  background-color: white;
  

  .header-container{
    max-width: 1200px;
    height: 110px;
    margin: 0 auto;
    display: flex;
    align-items: center;

    
    

    .logo-container{
      width: 40%;
    }

    .nav-container{
      width: 60%;
      

      ul{
        display: flex;
        justify-content: flex-end;

        li{
          list-style: none;
          margin: 0 10px;
          a{
            text-decoration: none;
            color: black;
            font-size: 13px;
            font-weight: 700;
          }
        }

      
      }
    
    }
  }
  
}

.active-page{
  border-bottom: 3px solid blue;
  
}


</style>