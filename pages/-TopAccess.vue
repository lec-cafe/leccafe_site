<template>
    <div class="p-access">
        <h1 class="p-access__title">Access</h1>
        <div class="p-access__map">
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3280.4242413943216!2d135.51525491526556!3d34.6944780910591!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x6000e6d71039b62d%3A0xbf66083b34cbf48e!2z44CSNTMwLTAwNDMg5aSn6Ziq5bqc5aSn6Ziq5biC5YyX5Yy65aSp5rqA77yS5LiB55uu77yY4oiS77yR77yXIOWkqea6gOapi-ODkeODvOOCr-ODk-ODqw!5e0!3m2!1sja!2sjp!4v1584948177414!5m2!1sja!2sjp" width="100%" height="100%" frameborder="0" style="border:0;" allowfullscreen="" aria-hidden="false" tabindex="0"></iframe>
        </div>
        <p class="p-access__address">
            530-0041<br>大阪府大阪市北区天満2丁目8-17<br>天満橋パークビル 501
        </p>
        <div class="p-access__btn">
            <router-link class="c-buttonWhite c-fs20 c-fwBold" to="">Google Map</router-link>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import "~/assets/scss/mixins/container.scss";

    .p-access {
        @include container();
        padding-left: 20px;
        padding-right: 20px;
        &__title {
            text-align: center;
            margin-bottom: 20px;
            font-size: 40px;
            letter-spacing: 0.2em;
            color: #E15F52;
            font-family: 'Voces';
        }
        &__map {
            width: 100%;
            height: 236px;
            margin-bottom: 20px;
        }
        &__address {
            width: 335px;
            font-size: 14px;
        }
        &__btn {
            width: 160px;
            height: 50px;
            margin: 0 auto;
            line-height: 50px;
        }
        &__btn a:hover {
            color: #E15F52;
        }
    }
</style>
