<script>

export default {

}
</script>

<template>
  <div class="menu-fixed">
    <div class="container d-flex align-items-center justify-content-between py-3">
      <div class="icon-box gap-2 d-flex align-items-center">
        <img src="../assets/images/logo.png" alt="">
      </div>

      <div class="box-nav-bar d-flex align-items-center">
        <h4>Home</h4>
        
        <div class="dropdown">
          <button class="btn dropdown-toggle d-flex align-items-center gap-2">
            <h4>Games</h4><i class="fa-solid fa-angle-down"></i>
          </button>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Games</a></li>
            <li><a class="dropdown-item" href="#">Games Details</a></li>
            <li><a class="dropdown-item" href="#">Match Details</a></li>
          </ul>
        </div>
        <div class="dropdown">
          <button class="btn dropdown-toggle d-flex align-items-center gap-2">
            <h4>Games</h4><i class="fa-solid fa-angle-down"></i>
          </button>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Shop</a></li>
            <li><a class="dropdown-item" href="#">Shop Single</a></li>
            <li><a class="dropdown-item" href="#">Shop Single 2</a></li>
            <li><a class="dropdown-item" href="#">Shop Single 3</a></li>
            <li><a class="dropdown-item" href="#">Shop Single 4</a></li>
          </ul>
        </div>
        <div class="dropdown">
          <button class="btn dropdown-toggle d-flex align-items-center gap-2">
            <h4>Games</h4><i class="fa-solid fa-angle-down"></i>
          </button>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">About Us</a></li>
            <li><a class="dropdown-item" href="#">Team</a></li>
            <li><a class="dropdown-item" href="#">Player</a></li>
            <li><a class="dropdown-item" href="#">Upcoming Matches</a></li>
            <li><a class="dropdown-item" href="#">FAQs</a></li>
            <li><a class="dropdown-item" href="#">Privacy Policy</a></li>
            <li><a class="dropdown-item" href="#">Terms</a></li>
            <li><a class="dropdown-item" href="#">Privacy Policy</a></li>
            <li><a class="dropdown-item" href="#">Terms</a></li>
            <li><a class="dropdown-item" href="#">Coming Soon</a></li>
            <li><a class="dropdown-item" href="#">Error</a></li>
          </ul>
        </div>
        <div class="dropdown">
          <button class="btn dropdown-toggle d-flex align-items-center gap-2">
            <h4>Games</h4><i class="fa-solid fa-angle-down"></i>
          </button>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Blog</a></li>
            <li><a class="dropdown-item" href="#">Blog Single</a></li>
          </ul>
        </div>
        <h4>Contact</h4>
      </div>

      <div class="box-cart d-flex align-items-center gap-3">
        <div class="box-img position-relative">
          <a href="#"><img src="../assets//images/icon/cart-icon.png" alt="">
            <!-- da togliere quando ci sarà jscript -->
            <span class="cart-q">03</span></a>
        </div>

        <div class="streaming-button d-flex align-items-center">
          <div class="small-outline">
            <div class="border-outline">
              <div class="box-live-button">
                <h5>LIVE STREAMING</h5>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;
.btn:hover h4,i{
  color: $colore2;
}
.dropdown{
  ul{
    background-color: rgb(27, 34, 46);
    li{
      a{
        color: white;
        font-size: 1.4rem;
        &:hover{
          background-color: transparent;
          color: $colore2;
        }
      }
    }
  }
}
.dropdown > .btn{
  

    i {
      padding-left: .2rem;
    }
}
.dropdown{
  i{
    color: white;
  }
}
.dropdown-toggle::after {
  display: none;
}
.dropdown:hover .dropdown-menu {
    display: block;
}

.menu-fixed {
  position: fixed;
  left: 50%;
  top: 0;
  translate: -50%;
  background-color: rgba(21, 25, 35, 0.8);
  width: 100vw;
  z-index: 1300;

  .container {
    height: 130px;
  }
}

.icon-box {
  color: white;
}

.box-nav-bar {
  h4 {
    cursor: pointer;
    color: white;
    margin: 0;

    
  }
}

.box-cart {


  .box-img {
    .cart-q {
      position: absolute;
      right: -25%;
      top: -25%;
      background-color: $colore1;
      border-radius: 50%;
      width: 1.2rem;
      height: 1.2rem;
      display: flex;
      justify-content: center;
      align-items: center;
      font-size: .9rem;
      color: black;
    }
  }

  .streaming-button {
    cursor: pointer;

    .small-outline {
      border: 1px solid $colore1;
      border-radius: 2rem;
    }

    .border-outline {
      border: 4px solid transparent;
      border-radius: 2rem;
    }

    .box-live-button {
      background-color: $colore1;
      padding: 1rem;
      border-radius: 2rem;
      display: flex;
      justify-content: center;
      align-items: center;

      h5 {
        margin: 0;
      }
    }

    &:hover .border-outline {
      border-color: $colore1;
    }
  }
}





</style>
