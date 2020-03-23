<template>
    <header class="l-header d-flex">
        <div class="l-header__title">
            <img src="~/assets/images/leccafe_logo.svg" alt="lec cafeロゴ">
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


    .l-header {
        width: 100%;
        height: 51px;
        box-sizing: border-box;
        box-shadow: 0px 4px 3px -3px #00000029;
        border-top: 3px solid #E15F52;
        padding: 9px;
        justify-content: space-between;
        align-items: center;
        background-color: #fff;
        position: fixed;
        z-index: 10;
        &__title {
            width: 120px;
            height: 34px;
        }
        &__buttons {
            height: 32px;
        }
        &__buttonsBtn {
            padding: 12px;
            font-size: 12px;
            margin-left: 7px;
        }
        &__buttonsBtn:nth-child(odd):hover {
            color: #E15F52;
        }
        &__buttonsBtn:nth-child(even):hover {
            color: #ffffff;
        }
    }

    @media screen and (min-width: 768px) {
        .l-header {
            height: 70px;
            &__buttons {
                height: 40px;
            }
            &__buttonsBtn {
                width: 180px;
                height: 40px;
                font-size: 18px;
                font-weight: bold;
            }
        }
    }
</style>