<script>
export default {
    props: {
        comic: Object
    },


    data() {
        return {
        }
    },

}

</script>

<template>
    <div class="img-container">
        <img :src="comic.thumb">

    </div>
    <span>{{ comic.series.toUpperCase() }}</span>

</template>

<style lang="scss">
.img-container {
    aspect-ratio: 1/1;
    overflow: hidden;
    margin-bottom: 1rem;
}
</style>