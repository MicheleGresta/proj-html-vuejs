<script>
export default {

}
</script>

<template>
    <div class="bg-color-container">
        <div class="container py-5">
            <h2>Futio Quick Facts</h2>
            <div class="box  py-5">
                <div class="card-container d-flex gap-3">
                    <div class="single-card d-flex flex-column gap-1 py-5">
                        <h1>1135</h1>
                        <p>Twitch Streams</p>
                    </div>
                    <div class="single-card d-flex flex-column gap-1 py-5">
                        <h1>44</h1>
                        <p>Total Games</p>
                    </div>
                    <div class="single-card d-flex flex-column gap-1 py-5">
                        <h1>982</h1>
                        <p>Youtube Streams</p>
                    </div>
                    <div class="single-card d-flex flex-column gap-1 py-5">
                        <h1>40</h1>
                        <p>Pro Team</p>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;
.bg-color-container{

    background-color: $colore3;

    .container{
        text-align: center;
        h2{
            color: $colore4;
            font-size: 3rem;
        }
        .card-container{

            .single-card{
                h1{
                    color: $colore4;
                }
                p{
                    color: $colore2;
                }
                border: 1px solid rgb(36, 36, 36);
                border-radius: 2rem;
                flex-basis: 0;
                flex-grow: 1;
                text-align: center;
            }
        }
    }
}

</style>
