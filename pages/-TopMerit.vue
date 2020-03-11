<template>
    <div class="p-top__merit">
        <div class="p-top_merit__contents">
            <h1 class="p-top__titles c-textRed">Merit</h1>

            <div class="p-top_merit__contents__section--right">
                <img class="p-top_merit__image c-mb20" src="~/assets/images/p-merit_img01@2x.png" alt="スクールイラスト">
                <div class="p-top_merit__contents__section--right__description">
                    <span class="p-top_merit__contents__section--right__description__number">01</span>
                    <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">制作会社運営スクール</h2>
                    <p class="c-textRed">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>

            <div class="p-top_merit__contents__section--left">
                <img class="p-top_merit__image c-mb20" src="~/assets/images/p-merit_img02@2x.png" alt="スクールイラスト">
                <div class="p-top_merit__contents__section--left__description">
                    <span class="p-top_merit__contents__section--left__description__number">02</span>
                    <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">講師はプロのエンジニア</h2>
                    <p class="c-textRed">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>

            <div class="p-top_merit__contents__section--right">
                <img class="p-top_merit__image c-mb20" src="~/assets/images/p-merit_img03@2x.png" alt="スクールイラスト">
                <div class="p-top_merit__contents__section--right__description">
                    <span class="p-top_merit__contents__section--right__description__number">03</span>
                    <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">個別のカリキュラム</h2>
                    <p class="c-textRed">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>

            <div class="p-top_merit__contents__section--left">
                <img class="p-top_merit__image c-mb20" src="~/assets/images/p-merit_img04@2x.png" alt="スクールイラスト">
                <div class="p-top_merit__contents__section--left__description">
                    <span class="p-top_merit__contents__section--left__description__number">02</span>
                    <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">講師はプロのエンジニア</h2>
                    <p class="c-textRed">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                </div>
            </div>

            <div class="p-top_merit__contents__document">
                <h3 class="c-fs14 c-fwBold c-textRed c-mb20">詳しく知りたい方は<br>まずは資料請求！</h3>
                <router-link class="c-buttonWhite c-fs20 c-fwBold" to="">資料請求</router-link>
            </div>
        </div>
    </div>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
    .p-top__merit {
        background:linear-gradient(90deg,#E15F52 0%,#E15F52 20%,#FFEDE6 20%,#FFEDE6 100%);
        text-align: center;
    }
    .p-top_merit__contents {
        h1 {
            padding-top: 40px;
            margin: 0;
        }
        &__section {
            &--right {
                width: 330px;
                margin: 0 0 0 auto;
                text-align: left;
                position: relative;
                &__description {
                    background-color: #fff;
                    width: 280px;
                    margin: 0 0 0 auto;
                    padding: 0 20px 30px;
                    text-align: center;
                    position: relative;
                    &__number {
                        position: relative;
                        top: -45px;
                        font-size: 60px;
                        color: #E15F52;
                        opacity:0.3;
                    }
                    p {
                        text-align: left;
                        color: #333333;
                        letter-spacing: 0.2em;
                    }
                }
            }
            &--left {
                width: 330px;
                margin: 0 auto 0 0;
                text-align: right;
                position: relative;
                &__description {
                    background-color: #fff;
                    width: 280px;
                    margin: 0 auto 0 0;
                    padding: 0 20px 30px;
                    text-align: center;
                    position: relative;
                    &__number {
                        position: relative;
                        top: -45px;
                        font-size: 60px;
                        color: #E15F52;
                        opacity:0.3;
                    }
                    p {
                        text-align: left;
                        color: #333333;
                        letter-spacing: 0.2em;
                    }
                }
            }
        }
        &__document {
            padding: 80px 0;
            h3 {
                letter-spacing: 0.1em;
                line-height: 1.5em;
            }
            a {
                width: 160px;
                height: 50px;
                margin: 0 auto;
            }
        }
    }
    .p-top_merit__image {
        position: relative;
        top: 45px;
        width: 140px;
        height: 150px;
        z-index: 1;
    }
</style>