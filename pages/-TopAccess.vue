<template>
    <div class="p-access">
        <h1 class="p-access__title">Access</h1>
        <div class="p-access__map"></div>
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
    .p-access {
        margin: 80px 0;
        &__title {
            text-align: center;
            margin: 0 auto 20px;
            font-size: 40px;
            letter-spacing: 0.2em;
            color: #E15F52;
            font-family: 'Voces';
        }
        &__map {
            width: 335px;
            height: 236px;
            background-color: gray;
            margin: 0 auto 20px;
        }
        &__address {
            width: 335px;
            margin: 0 auto 20px;
            font-size: 14px;
        }
        &__btn {
            width: 160px;
            height: 50px;
            margin: 0 auto;
            line-height: 50px;
        }
    }
</style>
