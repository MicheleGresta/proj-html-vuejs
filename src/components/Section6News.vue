<script>
export default {


}
</script>

<template>
    <div class="container">

        <div class="row pt-5 mt-3">
            <div class="col-3"></div>
            <div class="col-6">
                <div class="box d-flex flex-column gap-3 py-5 text-center">
                    <h4>Latest News</h4>
                    <h2>Stay Updated With Our Latest News Articles</h2>
                    <p>libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at
                        tellus.
                        Cras ultriciel ligula sed magna dictum porta.
                    </p>
                </div>
            </div>
        </div>

        <div class="row row-height">
            <div class="col-6">
                <div class="card d-flex flex-column">
                    <img src="../assets/images/blog-item-1.png" alt="">
                    <div class="card-body px-4 py-4 my-3">
                        <div class="box d-flex gap-3">

                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/clock.png" alt="">
                                <p>10 Min</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/eye.png" alt="">
                                <p>240</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/calendar.png" alt="">
                                <p>Apr 11,2022</p>
                            </div>

                        </div>
                        <h5 class="card-title">Secrets To An Amazing Role Playing Game</h5>
                    </div>
                </div>
            </div>
            <div class="col-6 col-news d-flex flex-column gap-4">
                <div class="card d-flex flex-row align-items-center">
                    <img src="../assets/images/blog-item-2.png" alt="">
                    <div class="card-body px-4">
                        <div class="box d-flex gap-3">

                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/clock.png" alt="">
                                <p>10 Min</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/eye.png" alt="">
                                <p>240</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/calendar.png" alt="">
                                <p>Apr 11,2022</p>
                            </div>

                        </div>
                        <h5 class="card-title">Top 5 Most Important Aspects Of Your Game</h5>
                    </div>
                </div>
                <div class="card d-flex flex-row align-items-center">
                    <img src="../assets/images/blog-item-3.png" alt="">
                    <div class="card-body px-4">
                        <div class="box d-flex gap-3">

                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/clock.png" alt="">
                                <p>10 Min</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/eye.png" alt="">
                                <p>240</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/calendar.png" alt="">
                                <p>Apr 11,2022</p>
                            </div>

                        </div>
                        <h5 class="card-title">The Rise Of Fantasy Sports And Online Games</h5>
                    </div>
                </div>
                <div class="card d-flex flex-row align-items-center">
                    <img src="../assets/images/blog-item-4.png" alt="">
                    <div class="card-body px-4">
                        <div class="box d-flex gap-3">

                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/clock.png" alt="">
                                <p>10 Min</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/eye.png" alt="">
                                <p>240</p>
                            </div>
                            <div class="inline-box d-flex gap-2 align-items-center">
                                <img src="../assets/images/icon/calendar.png" alt="">
                                <p>Apr 11,2022</p>
                            </div>

                        </div>
                        <h5 class="card-title">Benefits Of Gaming - PC And Video Games</h5>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;

.container{
    padding-bottom: 12rem;
}
.col-news{
    .card{
        img{
            border-radius: 1rem;
        }
    }
}

.card {
    border-radius: 1rem;
    background-color: $colore5;

    .card-body {
        
        h5 {
            color: $colore7;
            font-size: 2rem;
        }
    }

}

.box {
    h4 {
        color: $colore2;
    }

    h2 {
        color: $colore4;
        font-size: 3rem;
    }

    p {
        color: $colore4;
    }

    .inline-box {
        color: $colore2;

        p {
            color: $colore2;
            margin: 0;
        }
    }
    
}

.col-news {
    flex-basis: 0;
    flex-grow: 1;

}
</style>
