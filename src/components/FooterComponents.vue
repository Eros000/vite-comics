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

        <div class="links">
          <h3>
            DC COMICS
          </h3>

          <ul>

            <li>
              <a href="">Characters</a>
            </li>

            <li>
              <a href="">Comics</a>
            </li>

            <li>
              <a href="">Movies</a>
            </li>

            <li>
              <a href="">TV</a>
            </li>

            <li>
              <a href="">Games</a>
            </li>

            <li>
              <a href="">Videos</a>
            </li>

            <li>
              <a href="">News</a>
            </li>


          </ul>

          <h3>
            SHOP
          </h3>

          <ul>

            <li>
              <a href="">Shop DC</a>
            </li>

            <li>
              <a href="">Shop DC Collectibles</a>
            </li>

          </ul>

        </div>

        <div class="links">
          <h3>
            DC
          </h3>

          <ul>

            <li>
              <a href="">Terms Of Use</a>
            </li>

            <li>
              <a href="">Privacy policy (New)</a>
            </li>

            <li>
              <a href="">Ad Choices</a>
            </li>

            <li>
              <a href="">Advertising</a>
            </li>

            <li>
              <a href="">Jobs</a>
            </li>

            <li>
              <a href="">Subscriptions</a>
            </li>

            <li>
              <a href="">Talent Workshops</a>
            </li>

            <li>
              <a href="">CPSC Certificates</a>
            </li>

            <li>
              <a href="">Ratings</a>
            </li>

            <li>
              <a href="">Shop Help</a>
            </li>

            <li>
              <a href="">Contact Us</a>
            </li>


          </ul>
        </div>

        <div class="links">
          <h3>
            SITES
          </h3>

          <ul>

            <li>
              <a href="">DC</a>
            </li>

            <li>
              <a href="">MAD Magazine</a>
            </li>

            <li>
              <a href="">DC Kids</a>
            </li>

            <li>
              <a href="">DC Universe</a>
            </li>

            <li>
              <a href="">DC Power Visa</a>
            </li>

          </ul>
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

  .footer-center-nav{
    padding-left: 100px;
    display: flex;

    .links{
      padding-top: 20px;
      padding-left: 40px;

      h3{
        padding-top: 10px;
        color: white;
      }

      ul{
        

        li{
          padding-top: 15px;
          list-style: none;
          display: flex;
          align-items: center;
          


        
          a{
            text-decoration: none;
            color: white;
            font-size: 13px;
            
          }
        }
      }
    }
  }


  .footer-bottom{
    background-color: rgb(37, 37, 37);
    height: 150px;
    width: 100vw;
  }
}

</style>