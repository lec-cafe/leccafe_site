<template>
    <div>
        <div class="l-header d-flex">
            <div class="">
                <h1>lec café</h1>
            </div>
            <div class="d-flex">
                <router-link class="c-buttonWhite" to="">資料請求</router-link>
                <router-link class="c-buttonRed" to="">申し込み</router-link>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "DefaultHeader"
    }
</script>

<style lang="scss" scoped>
    @import "../assets/scss/component/button.scss";
    .l-header {
        height: 60px;
        box-sizing: border-box;
        border-bottom: 1px solid;
    }
</style>