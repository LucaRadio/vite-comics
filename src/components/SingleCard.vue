<script>
export default {
    props: {
        comicsList: Array
    },


    data() {
        return {
        }
    },

}

</script>

<template>
    <div class="col" v-for="singleCard in comicsList">
        <div class="img-container">
            <img :src="singleCard.thumb">

        </div>
        <span>{{ singleCard.series.toUpperCase() }}</span>

    </div>
</template>

<style lang="scss">
.img-container {
    aspect-ratio: 1/1;
    overflow: hidden;
    margin-bottom: 1rem;
}
</style>