<script>
export default {


}
</script>

<template>
    <div class="bg-color-container py-5">
        <div class="container d-flex flex-column align-items-center gap-5">
            <div class="box-title d-flex flex-column justify-content-center align-items-center gap-3 py-5">
                <h4>Trending Battle</h4>
                <h2>Keep Eyes & Manage Upcoming Battle</h2>
                <p>libero malesuada feugiaat. Vivamus magna justom Iacinia eget consectetur sed, convalida at tellus.
                    Cras ultricies ligula sed magna dictum porta.
                </p>
            </div>
            <div class="box-card gap-3">
                <div class="card d-flex align-items-center">
                    <div class="box-versus d-flex gap-5 py-5">
                        <img src="../assets/images/game-img-1.png" alt="">
                        <img src="../assets/images/verus-icon.png" alt="">
                        <img src="../assets/images/game-img-2.png" alt="">
                    </div>
                    <div class="box-card-time">
                        <h3>Call Of Duty</h3>
                        <p>December 25, 2022 4:00 PM</p>
                    </div>
                    <div class="box-socials py-4 d-flex gap-3">
                        <div class="box-yt d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/youtube-icon.png" alt="">
                            <p>YouTube</p>
                        </div>
                        <div class="box-ttv d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/twitch-icon.png" alt="">
                            <p>Twitch</p>
                        </div>
                    </div>
                </div>

                <div class="card d-flex align-items-center">
                    <div class="box-versus d-flex gap-5 py-5">
                        <img src="../assets/images/game-img-3.png" alt="">
                        <img src="../assets/images/verus-icon.png" alt="">
                        <img src="../assets/images/game-img-4.png" alt="">
                    </div>
                    <div class="box-card-time">
                        <h3>Legendary Battles</h3>
                        <p>December 25, 2022 4:00 PM</p>
                    </div>
                    <div class="box-socials py-4 d-flex gap-3">
                        <div class="box-yt d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/youtube-icon.png" alt="">
                            <p>YouTube</p>
                        </div>
                        <div class="box-ttv d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/twitch-icon.png" alt="">
                            <p>Twitch</p>
                        </div>
                    </div>
                </div>
                <div class="card d-flex align-items-center">
                    <div class="box-versus d-flex gap-5 py-5">
                        <img src="../assets/images/game-img-5.png" alt="">
                        <img src="../assets/images/verus-icon.png" alt="">
                        <img src="../assets/images/game-img-6.png" alt="">
                    </div>
                    <div class="box-card-time">
                        <h3>Nay Corral Gundown</h3>
                        <p>December 25, 2022 4:00 PM</p>
                    </div>
                    <div class="box-socials py-4 d-flex gap-3">
                        <div class="box-yt d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/youtube-icon.png" alt="">
                            <p>YouTube</p>
                        </div>
                        <div class="box-ttv d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/twitch-icon.png" alt="">
                            <p>Twitch</p>
                        </div>
                    </div>
                </div>
                <div class="card d-flex align-items-center">
                    <div class="box-versus d-flex gap-5 py-5">
                        <img src="../assets/images/game-img-7.png" alt="">
                        <img src="../assets/images/verus-icon.png" alt="">
                        <img src="../assets/images/game-img-8.png" alt="">
                    </div>
                    <div class="box-card-time">
                        <h3>League Of Legends</h3>
                        <p>December 25, 2022 4:00 PM</p>
                    </div>
                    <div class="box-socials py-4 d-flex gap-3">
                        <div class="box-yt d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/youtube-icon.png" alt="">
                            <p>YouTube</p>
                        </div>
                        <div class="box-ttv d-flex gap-2 align-items-center">
                            <img src="../assets/images/icon/twitch-icon.png" alt="">
                            <p>Twitch</p>
                        </div>
                    </div>
                </div>

            </div>
            <div class="dynamic-button d-flex">
                <div class="small-outline">
                    <div class="border-outline">
                        <div class="box-live-button">
                            <h5>VIEW ALL MATCH >></h5>
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
    background-color: $colore5;
    min-height: 100vh;
}

.container {

    .box-title {

        h4 {
            color: $colore2;
        }

        h2 {
            color: $colore7;
        }

        p {
            color: $colore4
        }
    }

    .small-outline {
        border: 1px solid $colore1;
        border-radius: 2rem;
        cursor: pointer;
        display: inline-block;
        margin: auto 0;

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





    .box-card {
        width: 100%;
        display: flex;
        flex-wrap: wrap;

        .card {
            background-color: $card-colore1;
            border: 1px solid $card-colore2;
            width: 49%;

            .box-card-time {
                background-color: $card-colore2;
                text-align: center;
                padding: 1rem 0;
                width: 100%;

                h3 {
                    color: $colore7;
                }

                p {
                    color: $colore2;
                }
            }

            .box-socials {
                p {
                    color: $colore7;
                    margin: 0;
                }
            }
        }

    }
}</style>
