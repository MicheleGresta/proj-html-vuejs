<script>
import FeedbackCard from './FeedbackCard.vue';
import {UsersFeedback} from "../store.js";

export default {
    components: {
        FeedbackCard
    },
    data() {
        return{
            UsersFeedback
        }
        
    }


}
</script>

<template>
    <div class="container">

        <div class="row pt-5 mt-3">
            <div class="col-3"></div>
            <div class="col-6">
                <div class="box d-flex flex-column gap-3 py-5 text-center">
                    <h4>Futio Feedback</h4>
                    <h2>What Our Gamers Say</h2>
                    <p>libero malesuada feugiat. Vivamus magna justo, lacinia eget consectetur sed, convallis at
                        tellus.
                        Cras ultriciel ligula sed magna dictum porta.
                    </p>
                </div>
            </div>
        </div>

        <div class="row py-3">
            <div class="col-1"></div>
            <div class="col-10">
                <div class="card-container d-flex gap-3">
                     <div class="card-settings" 
                    v-for="singleUserCard in UsersFeedback">
                        <FeedbackCard :singleUser="singleUserCard" />
                    </div>
                </div>
                   
                

            </div>
        </div>

        <div class="row bg-feedback">

            <div class="col-3"></div>

            <div class="col-6 position-relative">
                <div class="img-discount-1">
                    <img src="../assets/images/banner-item-obj1.png" alt="">
                </div>
                <div class="box d-flex flex-column align-items-center py-5 my-5 gap-4">
                    <h3>Make Offer</h3>
                    <h2>Get 70% Offer Discount</h2>
                    <p>Get Offers</p>
                </div>
                <div class="img-discount-2">
                    <img src="../assets/images/banner-item-obj2.png" alt="">
                </div>
            </div>

        </div>

    </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;
.card-container{
    overflow: auto;
    &::-webkit-scrollbar{
        background-color: grey;
        border-radius: 2rem;
    }
    &::-webkit-scrollbar-thumb{
        background-color: $colore5;
        border-radius: 2rem;
    }

    

}


.row-stats{
    overflow: auto;
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
}


.bg-feedback {
    background-image: url(../assets/images/banner-item-bg.png);
    background-size: cover;
    background-repeat: no-repeat;
    border-radius: 1rem;
    overflow: hidden;

    .img-discount-1 {
        position: absolute;
        top: 5rem;
        left: -22rem;
    }

    .img-discount-2 {
        position: absolute;
        top: -5rem;
        left: 38rem;
    }

    .box {
        color: $colore7;

        p {
            background-color: rgba(0, 0, 0, 0.425);
            padding: 1rem 3rem;
            border-radius: 2rem;

            &:hover {
                cursor: pointer;
            }
        }
    }
}</style>
