<script>

export default {


}
</script>

<template>
    <div class="bg-color-container">
        <div class="bg-img-container d-flex align-items-center gap-5">
            <img src="../assets/images/features-illus.png" alt="">
            <div class="container">
                <div class="box d-flex flex-column gap-3">
                    <h3>The Ultimate Competitive Gaming Platform</h3>
                    <h2>Make Your Mark On The Battle Field</h2>
                    <p>libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus,
                        Cras ultricies ligula sed magna dictum porta.</p>
                    <div class="box-titles d-flex flex-column gap-3">
                        <div class="single-box d-flex gap-3 align-items-center">
                            <img src="../assets/images/icon/features-icon-1.png" alt="">
                            <div class="box-title-section">
                                <h4>Live Streaming</h4>
                                <h5>Lorem ipsum dolor sit amet, consectetus adipiscing elit, sed do eiusmod tempor
                                    incididunt ut lavor.</h5>
                            </div>
                        </div>
                        <div class="single-box d-flex gap-3 align-items-center">
                            <img src="../assets/images/icon/features-icon-2.png" alt="">
                            <div class="box-title-section">
                                <h4>Great Tournament</h4>
                                <h5>Lorem ipsum dolor sit amet, consectetus adipiscing elit, sed do eiusmod tempor
                                    incididunt ut lavor.</h5>
                            </div>
                        </div>
                        <div class="single-box d-flex gap-3 align-items-center">
                            <img src="../assets/images/icon/features-icon-3.png" alt="">
                            <div class="box-title-section">
                                <h4>Gaming News</h4>
                                <h5>Lorem ipsum dolor sit amet, consectetus adipiscing elit, sed do eiusmod tempor
                                    incididunt ut lavor.</h5>
                            </div>
                        </div>
                    </div>
                    <div class="dynamic-button d-flex">
                        <div class="small-outline">
                            <div class="border-outline">
                                <div class="box-live-button">
                                    <h5 class="d-flex">PLAY NOW >></h5>
                                </div>
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
        height: 100%;

        .box {
            margin: 7rem;


            h3 {
                color: $colore2;
            }

            h2 {
                color: $colore7;
            }

            p {
                color: $colore4
            }

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

            .box-titles {

                .single-box {

                    h4,
                    h5 {
                        color: $colore7;
                    }
                }
            }
        }
    }
}
</style>
