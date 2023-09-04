<script>

export default {

    props: {
        singleUser: {
            type: Object,
        },
    },
    data() {
        return {

        };
    }
}
</script>

<template>
    <div class="box d-flex flex-column gap-3 p-4">
        <div class="star-box d-flex gap-1">
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
            <i class="fa-solid fa-star"></i>
        </div>
        <p>"Lorem ipsum dolor sit amet consectetur, adipisicing elit. Harum beatae perspiciatis aspernatur ducimus facere
            amet iure placeat numquam."</p>
        <div class="user-box d-flex gap-3 align-items-center">
            <div class="profile-pic">
                <img :src="singleUser.image" alt="">
            </div>
            <div class="user-info">
                <h4>{{ singleUser.name }}</h4>
                <p> {{ singleUser.country }}</p>
            </div>
        </div>

    </div>
</template>

<style scoped lang="scss">
@use "../variables" as *;

.box {
    background-color: $colore5;
    border-radius: 1.5rem;

    p {
        color: white;
    }
}

i {
    color: rgb(249, 188, 2);
}

.user-box {

    .user-info {
        p {
            color: $colore2;
        }

        h4 {
            color: $colore7;
        }
    }
}
</style>