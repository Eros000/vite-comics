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

  <footer>

    <div class="footer-top">

      <div class="footer-top-icons">

        <ul>

          <li>

            <img src="../assets/buy-comics-digital-comics.png" alt="">

            <a href="#">
              DIGITAL COMICS
            </a>

          </li>

          <li>

            <img src="../assets/buy-comics-merchandise.png" alt="">

            <a href="#">
              DC MERCHANDISE
            </a>

          </li>

          <li>

            <img src="../assets/buy-comics-subscriptions.png" alt="">

            <a href="#">
              SUBSCRIPTION
            </a>

          </li>

          <li>

            <img src="../assets/buy-comics-shop-locator.png" alt="">

            <a href="#">
              COMIC SHOP LOCATOR
            </a>

          </li>

          <li>

            <img src="../assets/buy-dc-power-visa.svg" alt="">

            <a href="#">
              DC POWER VISA
            </a>

          </li>

        </ul>

      </div>

    </div>

    <div class="footer-center">

      <div class="footer-center-nav">
        <div class="links1">

        </div>

        <div class="links1">
          <h3>
            DC COMICS
          </h3>

          <ul>
            <li>
              <a href=""></a>
            </li>
          </ul>
        </div>

        <div class="links2">
          
        </div>

        <div class="links3">
          
        </div>

      </div>

      <div class="footer-center-logo">
        <img src="../assets/dc-logo-bg.png" alt="">
      </div>

    </div>

    <div class="footer-bottom">

      <div class="footer-bottom-contacts">

      </div>
      
    </div>

  </footer>

</template>

<style scoped lang="scss">

footer{


  .footer-top{
    background-color: rgb(20, 94, 255);
    height: 150px;
    width: 100vw;

    .footer-top-icons{
      max-width: 1200px;
      margin: 0 auto;
      display: flex;
      align-items: center;
      

      ul{
        padding-top: 25px;
        display: flex;
        justify-content: space-between;

        li{
          list-style: none;
          display: flex;
          align-items: center;
          margin-left: 20px;

          img{
            width: 60px;
            
          }


          a{
            text-decoration: none;
            color: white;
            font-weight: 700;
            margin-left: 15px;
          }
        }
      }
    }
  }

  .footer-center{
    height: 400px;
    width: 100vw;
    background-image: url('../assets/footer-bg.jpg');
    display: flex;


    .footer-center-nav{
      width: 50%;


    }

    .footer-center-logo{
      width: 50%;
      overflow: hidden;
      position: relative;

      img{
        position: absolute;
        bottom: -100px;
      }
    }
  }
}

</style>