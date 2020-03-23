<template>
    <div class="p-merit">
        <div class="p-merit__container">
            <div class="p-merit__contents">
                <h1 class="p-merit__contentsTitle">Merit</h1>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img01@2x.png" alt="スクールイラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">01</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">制作会社運営スクール</h2>
                        <p class="p-merit__contentsSectionDescriptionText">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img02@2x.png" alt="講師イラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">02</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">講師はプロのエンジニア</h2>
                        <p class="p-merit__contentsSectionDescriptionText">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img03@2x.png" alt="会話イラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">03</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">個別のカリキュラム</h2>
                        <p class="p-merit__contentsSectionDescriptionText">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img04@2x.png" alt="作業イラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">04</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">アウトプット中心</h2>
                        <p class="p-merit__contentsSectionDescriptionText">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>

                <div class="p-merit__contentsDocument">
                    <h3 class="c-fs14 c-fwBold c-textRed c-mb20">詳しく知りたい方は<br>まずは資料請求！</h3>
                    <router-link to="">資料請求</router-link>
                </div>
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
@import "~/assets/scss/mixins/container.scss";

.p-merit {
        background:linear-gradient(90deg,#E15F52 0%,#E15F52 20%,#FFEDE6 20%,#FFEDE6 100%);
        &__container {
            @include container();
            padding-bottom: 80px;
        }
        text-align: center;
        &__contentsTitle {
            text-align: center;
            margin: 0 auto 0;
            padding-top: 10px;
            font-size: 40px;
            letter-spacing: 0.2em;
            color: #E15F52;
            font-family: 'Voces';
        }
        &__contentsSection {
            width: 100%;
            margin: 0 0 0 auto;
            text-align: left;
            position: relative;
        }
        &__contentsSectionImage {
            position: relative;
            top: 45px;
            width: 140px;
            height: 150px;
            z-index: 1;
        }
        &__contentsSectionDescription {
            background-color: #fff;
            width: 280px;
            margin: 0 0 0 auto;
            padding: 0 20px 30px;
            text-align: center;
            position: relative;
        }
        &__contentsSectionDescriptionNumber {
            position: relative;
            top: -45px;
            font-size: 60px;
            color: #E15F52;
            opacity:0.3;
        }
        &__contentsSectionDescriptionText {
                text-align: left;
                color: #333333;
                letter-spacing: 0.2em;
        }

        &__contentsSection:nth-child(odd) {
            margin: 0 auto 0 0;
            text-align: right;
        }
        &__contentsSection:nth-child(odd) &__contentsSectionDescription {
            margin: 0 auto 0 0;
        }
        &__contentsDocument {
            padding: 80px 0 0;
        }
        &__contentsDocument h3 {
            letter-spacing: 0.1em;
            line-height: 1.5em;
        }
        &__contentsDocument a {
            @include buttonWhite();
            width: 160px;
            height: 50px;
            margin: 0 auto;
            font-size: 20px;
            font-weight: bold;
        }
        &__contentsDocument a:hover {
            color: #E15F52;
        }
    }

    @media screen and (min-width: 768px) {
        .p-merit {
            background:linear-gradient(90deg,#E15F52 0%,#E15F52 43%,#FFEDE6 43%,#FFEDE6 100%);
            &__container {
                padding-bottom: 90px;
            }
            &__contentsTitle {
                padding-top: 40px;
            }
            &__contentsSection {
                width: 540px;
            }
            &__contentsSectionDescription {
                width: 540px;
                padding: 0 60px 60px;
            }
            &__contentsSectionDescription h2 {
                text-align: left;
            }
            &__contentsSection:nth-child(odd) &__contentsSectionDescriptionNumber:nth-child(odd) {
                right: -75px
            }
            &__contentsSection:nth-child(even) &__contentsSectionDescriptionNumber {
                left: -75px
            }
        }
    }
</style>
