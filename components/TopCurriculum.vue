<template>
    <div class="p-top__curriculum">
        <h1 class="p-top__titles c-textRed">Curriculum</h1>

        <div class="p-top__curriculum__section">
            <div class="p-top__curriculum__section__title c-mb20">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-top__curriculum__section__content">
                <img class="p-top__curriculum__image" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-top__curriculum__section__content__categories d-flex">
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-top__curriculum__section">
            <div class="p-top__curriculum__section__title c-mb20">
                <h3 class="c-textRed c-fs14 c-fwBold">仕事で活用できるスキルを</h3>
                <h2 class="c-fs24 c-fwBold">FRONTコース</h2>
            </div>
            <div class="p-top__curriculum__section__content">
                <img class="p-top__curriculum__image" src="~/assets/images/p-curriculum_img02@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-top__curriculum__section__content__categories d-flex">
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-top__curriculum__section">
            <div class="p-top__curriculum__section__title c-mb20">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-top__curriculum__section__content">
                <img class="p-top__curriculum__image" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-top__curriculum__section__content__categories d-flex">
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculum__section__content__categories__item">
                        <router-link class="c-fs14" to="">HTML</router-link>
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
    .p-top__curriculum {
        text-align: center;
        &__section {
            width: 330px;
            padding: 40px;
            margin: 0 auto;
            margin-bottom: 55px;
            background-color: #FFEDE6;
            &__title {
                text-align: left;
            }
            &__content {
                img {
                    width: 100px;
                    height: 90px;
                    margin-bottom: 10px;
                }
                p {
                    text-align: left;
                }
                &__categories {
                    padding: 0;
                    &__item {
                        list-style: none;
                        margin-right: 5px;
                        background-color: #E15F52;
                        padding: 5px 8px;
                        border-radius: 5px;
                        a {
                            color: #fff;
                            letter-spacing: 0.1em;
                        }
                    }
                }
            }
            &:nth-child(odd) {
                background-color: #fff;
                border: 2px solid #FFEDE6;
            }
        }
    }
    .p-top_curriculum__title-front {
        text-align: right;
    }
    .p-top_curriculum__image {
        width: 100px;
        height: 100px;
    }
    .p-top_curriculumHr {
        margin: 20px auto;
    }
</style>