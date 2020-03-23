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
                        <p class="p-reason__pointBoxDescription">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
                <div class="p-reason__point">
                    <img class="p-reason__pointImage" src="~/assets/images/p-reason_heading02@2x.png" alt="ハートのイラスト">
                    <div class="p-reason__pointBox">
                        <img class="p-reason__pointBoxImage" src="~/assets/images/p-reason_img02@2x.png" alt="">
                        <h3 class="c-fs20 c-textRed c-fwBold">個別カリキュラム</h3>
                        <p class="p-reason__pointBoxDescription">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>
            </div>   
            <div class="flex"> 
                <div class="p-reason__point 1">
                    <img class="p-reason__pointImage" src="~/assets/images/p-reason_heading03@2x.png" alt="PCのイラスト">
                    <div class="p-reason__pointBox">
                        <img class="p-reason__pointBoxImage" src="~/assets/images/p-reason_img03@2x.png" alt="">
                        <h3 class="c-fs20 c-textRed c-fwBold">自分で学べる学習スタイル</h3>
                        <p class="p-reason__pointBoxDescription">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                    </div>
                </div>

                <div class="p-reason__point">
                    <img class="p-reason__pointImage" src="~/assets/images/p-reason_heading04@2x.png" alt="カレンダーのイラスト">
                    <div class="p-reason__pointBox">
                        <img class="p-reason__pointBoxImage" src="~/assets/images/p-reason_img04@2x.png" alt="">
                        <h3 class="c-fs20 c-textRed c-fwBold">縛りなしで１ヶ月ごとの契約</h3>
                        <p class="p-reason__pointBoxDescription">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
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
@import "~/assets/scss/mixins/container.scss";

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
            height: 72px;
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
            height: 80px;
            position: relative;
            top: -50px;
        }
        &__pointBoxDescription {
            text-align: left;
            line-height: 2em;
            letter-spacing: 0.1em;
            font-size: 14px;
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
            &__pointImage {
                margin-left: 10px;
                margin-bottom: 20px;
            }
        }
    }
</style>
