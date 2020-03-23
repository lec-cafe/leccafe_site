<template>
    <div class="p-curriculum">
        <h1 class="c-titles c-textRed">Curriculum</h1>

        <div class="p-curriculum__section">
            <div class="p-curriculum__sectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-curriculum__sectionContent">
                <img class="p-curriculum__sectionContentImage" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p class="p-curriculum__sectionContentDescription">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-curriculum__categories">
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-curriculum__section">
            <div class="p-curriculum__sectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">フロントコース</h2>
            </div>
            <div class="p-curriculum__sectionContent">
                <img class="p-curriculum__sectionContentImage" src="~/assets/images/p-curriculum_img02@2x.png" alt="ウィンドウのイラスト">
                <p class="p-curriculum__sectionContentDescription">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-curriculum__categories">
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-curriculum__section">
            <div class="p-curriculum__sectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">BACKENDコース</h2>
            </div>
            <div class="p-curriculum__sectionContent">
                <img class="p-curriculum__sectionContentImage" src="~/assets/images/p-curriculum_img03@2x.png" alt="ウィンドウのイラスト">
                <p class="p-curriculum__sectionContentDescription">説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-curriculum__categories">
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="p-curriculum__categoriesItemText" to="">HTML</router-link>
                    </li>
                </ul>
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

    .p-curriculum {
        @include container();
        text-align: center;
        &__section {
            width: 90%;
            padding: 40px;
            margin: 0 auto;
            margin-bottom: 55px;
            background-color: #FFEDE6;
            position: relative;
        }
        &__section::after {
            content: '';
            display: block;
            width: 100%;
            height: 100%;
            border: 2px solid #FFEDE6;
            position: absolute;
            bottom: -3%;
            right: -5%;
            z-index: -1;
        }
        &__section:nth-child(odd) {
            background-color: #fff;
            border: 2px solid #FFEDE6;
        }
        &__section:nth-child(odd)::after {
            background-color: #FFEDE6;
            left: -5%;
            right: 5%;
        }
        &__sectionTitle {
            text-align: left;
            margin-bottom: 20px;
        }
        &__sectionContentImage {
            width: 100px;
            height: auto;
            margin-bottom: 10px;
        }
        &__sectionContentDescription {
            text-align: left;
        }
        &__categories {
            padding: 0;
            display: flex;
        }
        &__categoriesItem {
            list-style: none;
            margin-right: 5px;
            background-color: #E15F52;
            padding: 5px 8px;
            border-radius: 5px;
            line-height: 1;
        }
        &__categoriesItemText {
            color: #fff;
            letter-spacing: 0.1em;
            font-size: 14px;
        }
    }

    @media screen and (min-width: 768px) {
        .p-curriculum {
            &__section {
                width: 540px;
                height: 410px;
            }
            &__section:nth-child(even) {
                margin: 0 auto 150px 0;
            }
            &__section:nth-child(odd) {
                margin: 0 0 150px auto;
            }
            &__section:nth-child(even)::after {
                padding: 35% 50%;
                bottom: -15%;
                right: -15%;
            }
            &__section:nth-child(odd)::after {
                padding: 35% 50%;
                bottom: -15%;
                left: -15%;
            }
        }
    }
</style>