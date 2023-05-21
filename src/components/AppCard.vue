        <script>
        export default {
            props: {
                thumb: String,
                series: String,

    }
        };
        </script>


<template>
    <div>
        <div class="card"> 
            <img class="cards_img"
            :src="thumb" 
            :alt="series">
            <h2> {{ series }}</h2>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    .cards_img {
    aspect-ratio: 2/3;
    max-width: 150px;

}
.card {
    border: 1px solid white;
    text-align: center; 
    //CENTRA H2 DELLA CARD, CHE FORSE NON MI PIACE
}
h2 {
    margin-top: .6rem;
    font-size: 1rem;
}
</style>