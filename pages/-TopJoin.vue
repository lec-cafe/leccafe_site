<template>
    <div class="p-join">
        <h1>Join</h1>
        <div class="p-join__box">
            <h3>詳しく知りたい方は<br>まずは資料請求！</h3>
            <div class="p-join__buttons">
                <router-link to="">資料請求</router-link>
            </div>
            <div class="p-join__buttons">  
                <router-link to="">申し込み</router-link>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
@import "~/assets/scss/component/button.scss";

    .p-join {
        background-color: #E15F52;
        text-align: center;
        height: 560px;
        color: #FFFFFF;
        h1 {
            padding-top: 50px;
            font-family: Voces,Voces;
            font-size: 40px;
            letter-spacing: 0.2em;
        }
        &__box {
            color: #FFFFFF;
            border: solid 4px #ffffff;
            margin-top: 50px;
            height: 346px;
            margin-right: 20px;
            margin-left: 20px;
        }
        &__box h3 {
            font-size: 18px;
            margin-top: 60px;
            font-weight: bold;
            margin-bottom: 50px;
        }
        &__buttons:nth-child(even) a {
            @include buttonWhite();
            border: solid 2px #ffffff;
            color:#E15F52;
            margin: 0 auto;
            width: 160px;
            height: 50px;
            font-weight: bold;
            font-size: 20px;
            margin-bottom: 30px;
        }
        &__buttons:nth-child(odd) a {
            @include buttonRed();
            border: solid 2px #ffffff;
            color:#ffffff;
            margin: 0 auto;
            width: 160px;
            height: 50px;
            font-weight: bold;
            font-size: 20px;
        }
    }    
    @media screen and (min-width: 768px){
        .p-join__box {
            width: 728px;
            margin: 0 auto;
        }
        }
</style>