<template>
    <div class="p-reason" id="anchorReason">
        <div class="p-reason__container">
            <h1 class="c-titles c-textRed">Reason</h1>
            <div class="flex">
                <div class="p-reason__point 1">
                    <img class="p-reason__pointImage" src="~/assets/images/p-reason_heading01@2x.png" alt="手のイラスト">
                    <div class="p-reason__pointBox">
                        <img class="p-reason__pointBoxImage" src="~/assets/images/p-reason_img01@2x.png" alt="">
                        <h3 class="c-fs20 c-textRed c-fwBold">現場で使える技術を</h3>
                        <p class="p-reason__pointBoxDescription">制作現場でプロの技術者として活躍する講師のもと、HTMLやCSS、Vue.jsやLaravelといった注目度の高い技術をテーマに、「現場で使える」生きた制作技術の習得を目指しています。</p>
                    </div>
                </div>
                <div class="p-reason__point">
                    <img class="p-reason__pointImage" src="~/assets/images/p-reason_heading02@2x.png" alt="ハートのイラスト">
                    <div class="p-reason__pointBox">
                        <img class="p-reason__pointBoxImage" src="~/assets/images/p-reason_img02@2x.png" alt="">
                        <h3 class="c-fs20 c-textRed c-fwBold">個別カリキュラム</h3>
                        <p class="p-reason__pointBoxDescription">個人で作成しているサイトやプロジェクトなどの制作サポートを希望される方向けの、個別レッスン相談にも対応させていただきます。一般的な Web スクールよりも大幅に低価格で、短期集中型のスキルアップが可能です。</p>
                    </div>
                </div>
            </div>   
            <div class="flex"> 
                <div class="p-reason__point 1">
                    <img class="p-reason__pointImage" src="~/assets/images/p-reason_heading03@2x.png" alt="PCのイラスト">
                    <div class="p-reason__pointBox">
                        <img class="p-reason__pointBoxImage" src="~/assets/images/p-reason_img03@2x.png" alt="">
                        <h3 class="c-fs20 c-textRed c-fwBold">自分で学べる学習スタイル</h3>
                        <p class="p-reason__pointBoxDescription">Lec Cafe はそれぞれのゴールを決めるところからスタートします。講座の進むスピードもそれぞれのせスキルレベルに応じて柔軟に変化するため、自分でやればやるほどスキルアップにかかる時間や費用を調整できます。</p>
                    </div>
                </div>

                <div class="p-reason__point">
                    <img class="p-reason__pointImage" src="~/assets/images/p-reason_heading04@2x.png" alt="カレンダーのイラスト">
                    <div class="p-reason__pointBox">
                        <img class="p-reason__pointBoxImage" src="~/assets/images/p-reason_img04@2x.png" alt="">
                        <h3 class="c-fs20 c-textRed c-fwBold">縛りなしで１ヶ月ごとの契約</h3>
                        <p class="p-reason__pointBoxDescription">４回の技術指導で１ヶ月¥50,000(税別)から対応可能です。学生向けの無料プランもございます。制作したい内容をそえてご相談ください。</p>
                    </div>
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
@import "~/assets/scss/mixins.scss";

    .p-reason {
        background-color: #FFEDE6;
        text-align: left;
        padding: 0 20px 30px;
        &__container {
            @include container();
            padding-bottom: 0;
        }
        &__point {
            padding-bottom: 40px;
        }
        &__pointImage {
            width: 72px;
            height: auto;
            margin-left: 10px;
        }
        &__pointBox {
            background-color: #ffffff;
            text-align: center;
            position: relative;
        }
        &__pointBoxImage {
            display: inline-block;
            width: 80px;
            height: auto;
            position: relative;
            top: -50px;
        }
        &__pointBoxDescription {
            text-align: left;
            @include description();
            padding: 0 42px;
        }
        &__pointBox h3, &__pointBox p {
            position: relative;
            top: -30px;
        }
    }
    @media screen and (min-width: 780px) {
        .flex {
            display: flex;
            justify-content: space-between;
        }
        .p-reason {
            padding-bottom: 50px;
            &__point {
                height: auto;
                margin-top: 0px;
            }
            &__pointBox {
                width: 335px;
            }
            &__pointBox h3 {
                margin-bottom: 20px;
            }
            &__pointImage {
                margin-left: 10px;
                margin-bottom: 20px;
            }
        }
    }
</style>
