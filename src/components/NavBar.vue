<script>

export default {

}
</script>

<template>
  <div class="container d-flex align-items-center justify-content-between py-3">

    <div class="icon-box gap-2 d-flex align-items-center">
      <img src="../assets/images/logo.png" alt="">
    </div>

    <div class="box-nav-bar d-flex gap-3 align-items-center">
      <h4>Home</h4>
      <h4>Games<i class="fa-solid fa-angle-down"></i> </h4>
      <h4>Shop<i class="fa-solid fa-angle-down"></i></h4>
      <h4>Pages<i class="fa-solid fa-angle-down"></i></h4>
      <h4>Blog<i class="fa-solid fa-angle-down"></i></h4>
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
</template>

<style scoped lang="scss">
@use "../variables" as *;

.container{
  position: absolute;
  left: 50%;
  top: 0;
  translate: -50%;
}

.icon-box{
  color: white;
}

.box-nav-bar {
  h4 {
    cursor: pointer;
    color: white;
    margin: 0;

    &:hover {
      color: $colore2;
    }
    i{
      padding-left: .2rem;
    }
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
    .small-outline{
      border: 1px solid $colore1;
      border-radius: 2rem;
    }
    .border-outline{
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
    &:hover .border-outline{
      border-color: $colore1;
    }
  }
}
</style>
