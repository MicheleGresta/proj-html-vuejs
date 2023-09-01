<script>
export default {

}
</script>

<template>
  <div class="container d-flex">

    <div class="bg-box"></div>
    <div class="box d-flex flex-column gap-2 mt-5">
      <h3>Game With Live Streaming</h3>
      <h1>Future Of Esports</h1>
      <p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium</p>
      <div class="box-explore">
        <div class="streaming-button d-flex align-items-center gap-3">

          <div class="small-outline">
            <div class="border-outline">
              <div class="box-live-button">
                <h5>ESPLORE GAMES >></h5>
              </div>
            </div>
          </div>

          <div class="small-outline">
            <div class="border-outline-play">
              <div class="box-live-button-play">
                <img src="../assets/images/icon/play-icon.png" alt="">
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>

    <div class="soldier-img">
      <img src="../assets/images/index-banner-illus.png" alt="">
    </div>
  </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;

.container {
  margin-top: 7rem;
}

.box {
  h3 {
    color: $colore2;

  }

  h1 {
    color: $colore7;
    font-size: 5rem;
  }

  p {
    color: $colore4;
    font-size: 1.3rem;
  }
}

.streaming-button {


  .small-outline {
    border: 1px solid $colore1;
    border-radius: 2rem;
    cursor: pointer;

    &:hover .border-outline {
      border-color: $colore1;
    }

    &:hover .border-outline-play {
      border-color: $colore1;
    }

    .border-outline {
      border: 4px solid transparent;
      border-radius: 2rem;

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
    }
  }






  .box-live-button-play {
    background-color: $colore7;
    padding: 1rem;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .border-outline-play {
    border: 8px solid transparent;
    border-radius: 50%;
  }
}

.bg-box {
  background-image: url(../assets/images/game-controler.png);
  background-repeat: no-repeat;
}

.soldier-img {

  margin-right: -20%;
  margin-top: -10%;

}
</style>
