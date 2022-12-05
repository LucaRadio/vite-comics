<script>
export default {
    data() {
        return {
        }
    }
}
</script>
<template>
    <section>
        <div class="container">
            <div class="row row-cols-5 py-5">
                <div class="col">
                    <img src="../assets/buy-comics-digital-comics.png">
                    <small class="ms-2 text-white">DIGITAL COMICS</small>
                </div>
                <div class="col">
                    <img src="../assets/buy-comics-merchandise.png">
                    <small class="ms-2 text-white">DC MERCHANDISE</small>
                </div>
                <div class="col">
                    <img src="../assets/buy-comics-subscriptions.png">
                    <small class="ms-2 text-white">SUBSCRIPTION</small>
                </div>
                <div class="col">
                    <img src="../assets/buy-comics-shop-locator.png">
                    <small class="ms-2 text-white">COMIC SHOP LOCATION</small>
                </div>
                <div class="col">
                    <img src="../assets/buy-dc-power-visa.svg">
                    <small class="ms-2 text-white">DC POWER VISA</small>
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