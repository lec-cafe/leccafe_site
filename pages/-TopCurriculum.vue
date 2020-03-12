<template>
    <div class="p-curriculum">
        <h1 class="p-top__titles c-textRed">Curriculum</h1>

        <div class="p-curriculum__section">
            <div class="p-curriculum__sectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-curriculum__sectionContent">
                <img class="p-curriculumImage" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-curriculum__categories">
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-curriculum__section">
            <div class="p-curriculum__sectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-curriculum__sectionContent">
                <img class="p-curriculumImage" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-curriculum__categories">
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-curriculum__section">
            <div class="p-curriculum__sectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-curriculum__sectionContent">
                <img class="p-curriculumImage" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-curriculum__categories">
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-curriculum__categoriesItem">
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
    .p-curriculum {
        text-align: center;
        &__section {
            width: 330px;
            padding: 40px;
            margin: 0 auto;
            margin-bottom: 55px;
            background-color: #FFEDE6;
            position: relative;
            &Title {
                text-align: left;
                margin-bottom: 20px;
            }
            &Content {
                img {
                    width: 100px;
                    height: 90px;
                    margin-bottom: 10px;
                }
                p {
                    text-align: left;
                }
                .p-curriculum__categories {
                    padding: 0;
                    display: flex;
                    &Item {
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
            &::after {
                content: '';
                display: block;
                padding: 70% 50%;
                border: 2px solid #FFEDE6;
                position: absolute;
                bottom: -3%;
                right: -5%;
                z-index: -1;
            }
            &:nth-child(odd) {
                background-color: #fff;
                border: 2px solid #FFEDE6;
                &::after {
                    background-color: #FFEDE6;
                    left: -5%;
                    right: 5%;
                    padding: 70% 50%;
                }
            }
        }
    }
</style>