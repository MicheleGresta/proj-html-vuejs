<script>
export default {

}
</script>

<template>
    <div class="bg-container">
        <div class="container">
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

        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;

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
            .col-8{
                .row{
                    .col-3{
                        h4{
                            color: $colore7;
                            margin-bottom: 1.7rem;
                        }
                        .box-links{
                            color:$colore4;
                            h5{
                                &:hover{
                                    cursor: pointer;
                                    color: $colore1;
                                }
                            }
                            
                        }
                        .box-contact-links{
                            cursor: ;
                            h5{
                                color: $colore2;
                            }
                        }
                    }
                }
            }
        }

    }
}
</style>