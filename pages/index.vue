<template>
    <div>
        <div class="p-container">
            <div class="p-top__heading">
                <div>
                    <h1>lec café</h1>
                    <hr class="p-top__headingHr" width="100px" color="#E15F52" noshade>
                    <h2 class="c-fs20">手軽に始める<br>プログラミング<br>スクール</h2>
                </div>
                <div class="p-top_heading--1 c-mb20">
                    <img class="p-top_headingImage" src="~/assets/images/top_img1.jpg" alt="">
                    <p>Lec Cafeは学生や社会人を対象とした<br>大阪のプログラミングスクールです。</p>
                </div>
                <div class="p-top_heading__buttons c-mb40">
                    <router-link class="c-buttonWhite c-fs20" to="">資料請求</router-link>
                    <router-link class="c-buttonRed c-fs20" to="">申し込み</router-link>
                </div>
            </div>
            <div class="p-top__merit">
                <div class="p-top_merit__contents">
                    <h1 class="p-top__titles c-textRed">Merit</h1>
                    <div>
                        <img class="p-top_merit__image c-mb20" src="~/assets/images/top_img1.jpg" alt="">
                        <h2 class="c-textRed c-mb20">制作会社運営スクール</h2>
                        <p class="c-textRed c-mb40">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                    <div>
                        <img class="p-top_merit__image c-mb20" src="~/assets/images/top_img1.jpg" alt="">
                        <h2 class="c-textRed c-mb20">講師はプロのエンジニア</h2>
                        <p class="c-textRed c-mb40">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                    <div>
                        <img class="p-top_merit__image c-mb20" src="~/assets/images/top_img1.jpg" alt="">
                        <h2 class="c-textRed c-mb20">個別のカリキュラム</h2>
                        <p class="c-textRed c-mb40">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                    <div>
                        <img class="p-top_merit__image c-mb20" src="~/assets/images/top_img1.jpg" alt="">
                        <h2 class="c-textRed c-mb20">アウトプット中心</h2>
                        <p class="c-textRed c-mb40">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                    <div>
                        <h3 class="c-fs20 c-textRed c-mb20">詳しく知りたい方は<br>まずは資料請求！</h3>
                        <router-link class="c-buttonWhite c-mb60" to="">資料請求</router-link>
                    </div>
                </div>
            </div>
            <div class="p-top__curriculum">
                <h1 class="p-top__titles c-textRed">Curriculum</h1>
                <div class="p-top__curriculum__beginers">
                    <div class="p-top_curriculum__title c-mb20">
                        <h3 class="c-textRed c-fs16">基礎からしっかり学びたいあなたに</h3>
                        <h2>初心者向けコース</h2>
                    </div>
                    <div class="p-top_curriculum__content d-flex">
                        <img class="p-top_curriculum__image" src="~/assets/images/top_img1.jpg" alt="">
                        <img class="p-top_curriculum__image" src="~/assets/images/top_img1.jpg" alt="">
                        <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
                <hr class="p-top_curriculumHr" width="295px" color="#FFEDE6" noshade>
                <div class="p-top__curriculum__front">
                    <div class="p-top_curriculum__title-front c-mb20">
                        <h3 class="c-textRed c-fs16">仕事で活用できるスキルを</h3>
                        <h2>FRONTコース</h2>
                    </div>
                    <div class="p-top_curriculum__content d-flex">
                        <img class="p-top_curriculum__image" src="~/assets/images/top_img1.jpg" alt="">
                        <img class="p-top_curriculum__image" src="~/assets/images/top_img1.jpg" alt="">
                        <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
                <hr class="p-top_curriculumHr" color="#FFEDE6" width="295px" noshade>
                <div class="p-top__curriculum__backend">
                    <div class="p-top_curriculum__title c-mb20">
                        <h3 class="c-textRed c-fs16">バックエンドをやってみたい</h3>
                        <h2>BACKENDコース</h2>
                    </div>
                    <div class="p-top_curriculum__content d-flex">
                        <img class="p-top_curriculum__image" src="~/assets/images/top_img1.jpg" alt="">
                        <img class="p-top_curriculum__image" src="~/assets/images/top_img1.jpg" alt="">
                        <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
            </div>
            <div class="p-top__reason">
                <h1 class="p-top__titles c-textRed">Reason</h1>
                <div class="p-top_reason__point01">
                    <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                    <div class="p-top_reason__box">
                        <h3>現場で使える技術を</h3>
                        <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
                <div class="p-top_reason__point02">
                    <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                    <div class="p-top_reason__box">
                        <h3>個別カリキュラム</h3>
                        <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
                <div class="p-top_reason__point03">
                    <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                    <div class="p-top_reason__box">
                        <h3>自分で学べる学習スタイル</h3>
                        <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
                <div class="p-top_reason__point04">
                    <img class="p-top_reason__image" src="~/assets/images/top_img1.jpg" alt="">
                    <div class="p-top_reason__box">
                        <h3>縛りなしで１ヶ月ごとの契約</h3>
                        <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
            </div>
            <div class="p-top__access">
                <h1 class="p-top__titles c-textRed">Access</h1>
                <img width="335px" height="235px" src="~/assets/images/top_img1.jpg" alt="">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
            </div>
            <div class="p-top__join">
                <h1>Join</h1>
                <div class="p-top_join__box">
                    <h3>詳しく知りたい方は<br>まずは資料請求！</h3>
                    <button>資料請求</button>
                    <button>申し込み</button>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    // import DefaultHeader from "./components/layout/header";

    export default {
        name: "index",
        // components: { DefaultHeader }
    }
</script>

<style lang="scss" scoped>
    @import "../assets/scss/mixins/container.scss";
    @import "../assets/scss/component/button.scss";
    .p-container {
        @include container();
    }
    p {
        font-size: 14px;
    }
    .p-top__headingHr {
        margin: 10px 0;
    }
    .p-top_heading--1 {
        text-align: right;
    }
    .p-top_headingImage {
        width: 290px;
        height: 230px;
    }
    .p-top_heading__buttons {
        display: flex;
        justify-content: space-around;
    }
    .p-top__titles {
        text-align: center;
        margin: 40px auto;
        font-size: 40px;
    }
    .p-top__merit {
        background-color: #FFEDE6;
        text-align: center;
    }
    .p-top_merit__contents {
        width: 295px;
        margin: 0 auto;
    }
    .p-top_merit__image {
        width: 180px;
        height: 180px;
    }
    .p-top__curriculum {
        text-align: center;
    }
    .p-top_curriculum__title {
        text-align: left;
    }
    .p-top_curriculum__title-front {
        text-align: right;
    }
    .p-top_curriculum__content {
        width: 295px;
        margin: 0 auto;
    }
    .p-top_curriculum__image {
        width: 100px;
        height: 100px;
    }
    .p-top_curriculumHr {
        margin: 20px auto;
    }
    .p-top__reason {
        background-color: #FFEDE6;
        text-align: center;
    }
    .p-top_reason__image {
        width: 120px;
        height: 120px;
    }
    .p-top_reason__box {
        background-color: #ffffff;
        border-radius: 10px;
    }
    .p-top__join {
        background-color: #E15F52;
        text-align: center;
    }
    .p-top_join__box {
        border: solid 3px #ffffff;
        border-radius: 10px;
    }
</style>