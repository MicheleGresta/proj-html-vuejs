<script>
export default {

}
</script>

<template>
    <div class="bg-container">
        <div class="container position-relative">
            <div class="row">
                <div class="col-4">
                    <img src="../assets/images/logo.png" alt="">
                    <p class="py-4">
                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Adipisci blanditiis soluta error.
                    </p>

                    <div class="box-socials d-flex gap-2">
                        <i class="fa-brands fa-youtube"></i>
                        <i class="fa-brands fa-twitch"></i>
                        <i class="fa-brands fa-facebook"></i>
                        <i class="fa-brands fa-instagram"></i>
                    </div>


                </div>
                <div class="col-8">
                    <div class="row">

                        <div class="col-3">
                            <h4>Quick Links</h4>
                            <div class="box-links">
                                <h5>Games</h5>
                                <h5>Latest Tournament</h5>
                                <h5>Shop</h5>
                                <h5>Blog</h5>
                                <h5>Contact</h5>
                            </div>
                        </div>

                        <div class="col-3">
                            <h4>Help</h4>
                            <div class="box-links">
                                <h5>Faqs</h5>
                                <h5>Terms & Conditions</h5>
                                <h5>Privacy</h5>
                            </div>
                        </div>

                        <div class="col-3">
                            <h4>Follow Us</h4>
                            <div class="box-links">
                                <h5>Facebook</h5>
                                <h5>Twitter</h5>
                                <h5>Instagram</h5>
                                <h5>Youtube</h5>
                                <h5>Github</h5>
                            </div>
                        </div>

                        <div class="col-3">
                            <h4>Contact</h4>
                            <div class="box-links box-contact-links">
                                <h5>Location:
                                    <h6>4 Mayfield, Buckden, PE19 5SZ</h6>
                                </h5>
                                <h5>Phone:
                                    <h6>(302) 555-0107</h6>
                                </h5>

                            </div>
                        </div>

                    </div>
                </div>
            </div>

            <div class="row floating-news">
                <div class="col-1"></div>
                <div class="col-10">
                    <div class="bg-row row d-flex align-items-center">
                        <div class="col-7">
                            <h3>Subscribe Newsletter</h3>
                            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsa ipsum quibusdam molestias quo
                                architecto enim tempore.</p>
                        </div>
                        <div class="col-5">
                            <div class="input-group mb-3">
                                <input type="text" class="form-control" placeholder="Enter your email" aria-label="Username"
                                    aria-describedby="basic-addon1">
                                <span class="input-group-text" id="basic-addon1">
                                    <img src="../assets/images/icon/send-icon.png" alt="">
                                </span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>


        </div>
    </div>
    <div class="bg-container-2">
        <div class="container">
            <div class="row row-footer">
                <div class="col-4"></div>
                <div class="col-4 d-flex align-items-center">
                    <p>Copyright &#xA9; 2022 <span class="color-text">FUTIO</span>. All right reserved.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;

.bg-container-2 {
    background-color: rgb(27, 33, 45);

    p {
        color: white;
        margin: 0;
        padding: 2rem;
        .color-text{
            color: $colore2;
        }
    }
}

.floating-news {
    position: absolute;
    top: -25%;
}

.bg-row {
    background-color: rgb(48, 65, 95);
    padding: 4rem 2rem;
    border-radius: 2rem;
    color: white;
}

.form-control {
    background-color: rgb(67, 83, 116);
    border: none;

    &::placeholder {
        color: white;
    }
}

.input-group-text {
    cursor: pointer;
    background-color: rgb(67, 83, 116);
    border: none;

    img {
        background-color: $colore2;
        border-radius: 50%;
        padding: .3rem;
    }
}



.bg-container {
    background-color: $card-colore1;

    .container {
        padding-top: 12rem;
        padding-bottom: 7rem;

        .row {
            .col-4 {
                color: $colore4;

                .box-socials {
                    flex-basis: 0;
                    flex-grow: 1;

                    i {
                        cursor: pointer;
                        border: 1px solid rgb(77, 75, 75);
                        padding: .7rem;
                        border-radius: 50%;
                    }
                }


            }

            .col-8 {
                .row {
                    .col-3 {
                        h4 {
                            color: $colore7;
                            margin-bottom: 1.7rem;
                        }

                        .box-links {
                            color: $colore4;

                            h5 {
                                &:hover {
                                    cursor: pointer;
                                    color: $colore2;
                                }
                            }

                        }

                        .box-contact-links {

                            h5 {
                                color: $colore2;
                            }
                        }
                    }
                }
            }
        }

    }
}</style>