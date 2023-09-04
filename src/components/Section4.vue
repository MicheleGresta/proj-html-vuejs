<script>
export default {


}
</script>

<template>
    <div class="bg-color-container">
        <div class="bg-img-container">
            <div class="container">
                <div class="row">
                    <div class="col-1"></div>
                    <div class="col-10">
                        <div class="box d-flex flex-column gap-3 py-5 text-center">
                            <h4>Live Streaming</h4>
                            <h2>Watch The Streams</h2>
                            <p>libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at
                                tellus.
                                Cras ultriciel ligula sed magna dictum porta.
                            </p>
                        </div>
                    </div>
                </div>
                <div class="live-box row">
                    <div class="col-1"></div>
                    <div class="box-player col-10 d-flex flex-column justify-content-between my-5">

                        <div class="row">
                            <div class="col-11"></div>
                            <div class="live-button d-flex gap-2 justify-content-center align-items-center col-1">
                                <img src="../assets/images/icon/live-icon.png" alt="">
                                Live
                            </div>
                        </div>
                        <div class="row">
                            <div class="col-4"></div>
                            <div
                                class="col-4 text-center box-play-center gap-3 d-flex flex-column align-items-center justify-content-center">
                                <div class="dynamic-play d-flex">
                                    <div class="small-outline">
                                        <div class="border-outline-play">
                                            <div class="box-live-button-play">
                                                <img src="../assets/images/icon/play-icon.png" alt="">
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <h3>League Of Legends</h3>
                            </div>
                        </div>


                        <div class="row box-counters">
                            <div class="col-1 box d-flex gap-1">
                                <h5>356.599</h5>
                                <h6>Viewers</h6>
                            </div>
                            <div class="col-1"></div>
                            <div class="col-1 box d-flex gap-1">
                                <h5>23.599</h5>
                                <h6>Likes</h6>
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

.bg-color-container {
    background-color: $colore3;
    height: 1080px;

    .bg-img-container {
        
        background-image: url(../assets/images/live-streaming-bg.png);
        background-repeat: no-repeat;
        background-size: cover;

        .container {
            .box {
                h4 {
                    color: $colore2;
                }

                h2 {
                    color: $colore4;
                    font-size: 4rem;
                }

                p {
                    color: $colore4;
                }
            }

            .live-box {
                background-image: url(../assets/images/video-bg.png);
                background-repeat: no-repeat;
                background-size: cover;
                aspect-ratio: 2/1;
                border-radius: 2rem;

                .box-player {


                    .live-button {
                        background-color: rgb(254, 154, 49);
                        border-radius: 2rem;
                        padding: .2rem 0;

                        cursor: pointer;

                        img {
                            width: auto;
                        }


                    }

                    .box-play-center {
                        h3{
                            color: $colore7;
                        }
                        .dynamic-play {
                            .small-outline {
                                border: 1px solid $colore1;
                                border-radius: 2rem;
                                cursor: pointer;

                                &:hover .border-outline-play {
                                    border-color: $colore1;
                                }


                                .border-outline-play {
                                    border: 8px solid transparent;
                                    border-radius: 50%;

                                    .box-live-button-play {
                                        background-color: $colore7;
                                        padding: 1rem;
                                        border-radius: 50%;
                                        display: flex;
                                        justify-content: center;
                                        align-items: center;


                                    }
                                }




                            }
                        }
                    }
                    .box-counters{
                        h5{
                            color: $colore2;
                        }
                        h6{
                            color: $colore7;
                            font-size: 1.3rem;
                        }
                    }

                }
            }
        }
    }
}
</style>
