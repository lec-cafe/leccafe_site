<template>
    <div class="p-merit" id="anchorMerit">
        <div class="p-merit__container">
            <div class="p-merit__contents">
                <h1 class="p-merit__contentsTitle">Merit</h1>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img01@2x.png" alt="スクールイラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">01</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">制作会社運営スクール</h2>
                        <p class="p-merit__contentsSectionDescriptionText">スキル的な部分を現場の延長線で。技術顧問だから。実際のWeb制作会社の教育プログラムをそのまま学べます。実務で活かせるのはもちろん、実質OJTを受けているのと同じです。</p>
                    </div>
                </div>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img02@2x.png" alt="講師イラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">02</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">講師はプロのエンジニア</h2>
                        <p class="p-merit__contentsSectionDescriptionText">PHP・Vue.jsを中心とするWeb制作を進めながら、技術顧問という肩書で関西の様々な制作現場の業務改善に取り組んでいます。制作現場での技術的な指導や設計レビュー、業務改善提案のほか、イベント・セミナーでの登壇など、「作る」だけでなく「伝える」ことに重きを置いた活動を続けてきました。</p>
                    </div>
                </div>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img03@2x.png" alt="会話イラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">03</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">個別のカリキュラム</h2>
                        <p class="p-merit__contentsSectionDescriptionText">個人で作成しているサイトやプロジェクトなどの制作サポートを希望される方向けの個別レッスン相談にも対応させていただきます。一般的なWebスクールよりも大幅に低価格で、短期集中型のスキルアップが可能です。</p>
                    </div>
                </div>

                <div class="p-merit__contentsSection">
                    <img class="p-merit__contentsSectionImage" src="~/assets/images/p-merit_img04@2x.png" alt="作業イラスト">
                    <div class="p-merit__contentsSectionDescription">
                        <span class="p-merit__contentsSectionDescriptionNumber">04</span>
                        <h2 class="c-textRed c-mb20 c-fs20 c-fwBold">アウトプット中心</h2>
                        <p class="p-merit__contentsSectionDescriptionText">聞くだけではなく、手を動かしながら実際に体験して学べるので短い時間でしっかり達成感を体感出来ます。ずっと気になっていたあの技術や、一人ではなかなか始められなかったコトなど気軽に相談できる環境で学んでみませんか？</p>
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
@import "~/assets/scss/mixins.scss";

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
            height: auto;
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
                @include description();
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
            @include buttonWhiteHover();
        }
    }

    @media screen and (min-width: 768px) {
        .p-merit {
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

    @media screen and (min-width: 1024px) {
        .p-merit {
            background: linear-gradient(90deg, #E15F52 0%, #E15F52 43%, #FFEDE6 43%, #FFEDE6 100%);
        }
    }
</style>
