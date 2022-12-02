<script>
export default {

}
</script>
<template>
    <section class="bg-dark py-4">
        <div class="container d-flex justify-content-between">
            <button>SIGN-UP NOW!</button>
            <div class="d-flex align-items-center">
                <div class="follow">FOLLOW US</div>
                <div class="icon-container">
                    <img src="../assets/footer-facebook.png">
                </div>
                <div class="icon-container">
                    <img src="../assets/footer-twitter.png">
                </div>
                <div class="icon-container">
                    <img src="../assets/footer-youtube.png">
                </div>
                <div class="icon-container">
                    <img src="../assets/footer-pinterest.png">
                </div>
                <div class="icon-container">
                    <img src="../assets/footer-periscope.png">
                </div>
            </div>

        </div>
    </section>
</template>
<style lang="scss" scope>
@use '../styles/general.scss' as*;

button {
    border: 2px solid $color-primary-dc;
    padding: .5rem .75rem;
    background-color: transparent;
    color: white;
}

.follow {
    color: $color-primary-dc;
    font-size: 20px;
    margin-right: 1rem;

}

.icon-container {
    padding: .5rem;
}
</style>