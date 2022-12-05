<script>
export default {
    data() {
        return {
            merchList: [
                {
                    text: "DIGITAL COMICS",
                    url: "buy-comics-digital-comics.png"
                },
                {
                    text: "DC MERCHANDISE",
                    url: "buy-comics-merchandise.png"
                },
                {
                    text: "SUBSCRIPTION",
                    url: "buy-comics-subscriptions.png"
                },
                {
                    text: "COMIC SHOP LOCATION",
                    url: "buy-comics-shop-locator.png"
                },
                {
                    text: "DC POWER VISA",
                    url: "buy-dc-power-visa.svg"
                },
            ]
        }
    },
    methods: {
        getUrl(item) {
            return new URL(`../assets/${item.url}`, import.meta.url);
        }
    }
}
</script>
<template>
    <section>
        <div class="container">
            <div class="row row-cols-5 py-5">

                <div class="col" v-for="item in merchList">
                    <img :src="getUrl(item)">
                    <small class="ms-2 text-white">{{ item.text }}</small>
                </div>

            </div>
        </div>

    </section>
</template>
<style scope lang="scss">
@use '../styles/general' as *;

section {
    background-color: $color-primary-dc;

    .col {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .col img {
        width: 40px;
        height: 40px;
        object-fit: contain;
    }

    .col>small {
        font-size: 10px;
    }
}
</style>