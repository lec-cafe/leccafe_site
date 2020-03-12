<template>
    <header class="l-header d-flex">
        <div class="l-header__title">
            <img src="~/assets/images/leccafe_logo.svg" alt="">
        </div>
        <div class="l-header__buttons d-flex">
            <router-link class="l-header__buttonsBtn c-buttonWhite" to="">資料請求</router-link>
            <router-link class="l-header__buttonsBtn c-buttonRed" to="">申し込み</router-link>
        </div>
    </header>
</template>

<script>
    export default {
    }
</script>

<style lang="scss" scoped>
    @import "~/assets/scss/component/button.scss";

    $defaultHeaderHeight: 51px;

    .l-header {
        height: $defaultHeaderHeight;
        box-sizing: border-box;
        border-bottom: 1px solid #00000029;
        padding: 9px;
        justify-content: space-between;
        &__title {
            width: 120px;
            height: 34px;
            h1 {
                font-size: 30px;
            }
        }
        &__buttons {
            height: 32px;
            &Btn {
                padding: 12px;
                font-size: 12px;
                margin-left: 7px;
            }
        }
    }
</style>