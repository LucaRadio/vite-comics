<script>
export default {
    data() {
        return {
            listItems: [
                // Messo per ora sotto forma di stringhe
                'CHARACTERS',
                'COMICS',
                'MOVIES',
                'TV',
                'GAMES',
                'COLLECTIBLES',
                'VIDEOS',
                'FANS',
                'NEWS',
                'SHOP'
            ]
        }
    }
}
</script>


<template>
    <header class="d-flex">
        <img src="../assets/dc-logo.png" alt="Dc Logo">
        <ul>
            <li v-for="item in listItems">
                <a href="#"> {{ item }}</a>
            </li>
        </ul>

    </header>

</template>


<style scope lang="scss">
@use '../styles/general.scss' as *;

header {
    display: flex;
    justify-content: space-between;

    img {
        display: inline-block;
        width: 50px;
        margin: 1rem;
    }

    ul {
        display: flex;
        margin: 0;
        padding: 0;

        li {
            display: flex;

            &:hover {
                border-bottom: 3px solid $color-primary-dc;
            }
        }

        & a {
            padding: 0rem .5rem;
            display: flex;
            align-items: center;
            font-size: 12px;
            color: black;
            font-weight: bold;
            text-decoration: none;

            &:hover {
                color: $color-primary-dc;

            }
        }
    }
}
</style>