<script>
import SocialBanner from './SocialBanner.vue';

export default {
    components: { SocialBanner }
}
</script>
<template>
    <footer>
        <div class="container">
            <div class="row justify-content-between">
                <div class="col-5 text-white">
                    <div class="row py-4">
                        <div class="col-4">
                            <span>DC COMICS</span>
                            <ul>
                                <li>Characters</li>
                                <li>Comics</li>
                                <li>Movies</li>
                                <li>TV</li>
                                <li>Games</li>
                                <li>Videos</li>
                                <li>News</li>
                            </ul>
                            <span>SHOP</span>
                            <ul>
                                <li>Shop DC</li>
                                <li>Shop DC Collectibles</li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <span>DC</span>
                            <ul>
                                <li>Term Of Use</li>
                                <li> Privacy polici (New)</li>
                                <li>Ad Choices</li>
                                <li>Advertising</li>
                                <li>Jobs</li>
                                <li>Subscriptions</li>
                                <li>Talent Workshop</li>
                                <li>CPSC Certificates</li>
                                <li>Ratings</li>
                                <li>Shop Help</li>
                                <li>Contact Us</li>
                            </ul>
                        </div>
                        <div class="col-4">
                            <span>SITES</span>
                            <ul>
                                <li>DC</li>
                                <li>MAD Magazine</li>
                                <li>DC Kids</li>
                                <li>DC Universe</li>
                                <li>DC Power Vista</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-5 dc"></div>
            </div>
        </div>
    </footer>
    <SocialBanner />
</template>





<style scope lang="scss">
@use '../styles/general.scss' as*;

footer {
    background-image: url("../assets/footer-bg.jpg");
}

span {
    display: inline-block;
    margin-bottom: .75rem;
}

.col-4 ul {
    list-style: none;
    padding: 0;

    &>li {
        font-size: small;
        color: #8f939a;
    }
}

.dc {
    background-image: url('../assets/dc-logo-bg.png');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}
</style>