<template>
    <div class="p-top__curriculum">
        <h1 class="p-top__titles c-textRed">Curriculum</h1>

        <div class="p-top__curriculumSection">
            <div class="p-top__curriculumSectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-top__curriculumSectionContent">
                <img class="p-top__curriculumImage" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-top__curriculumSectionContentCategories">
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-top__curriculumSection">
            <div class="p-top__curriculumSectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-top__curriculumSectionContent">
                <img class="p-top__curriculumImage" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-top__curriculumSectionContentCategories">
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                </ul>
            </div>
        </div>

        <div class="p-top__curriculumSection">
            <div class="p-top__curriculumSectionTitle">
                <h3 class="c-textRed c-fs14 c-fwBold">基礎からしっかり学びたいあなたに</h3>
                <h2 class="c-fs24 c-fwBold">初心者向けコース</h2>
            </div>
            <div class="p-top__curriculumSectionContent">
                <img class="p-top__curriculumImage" src="~/assets/images/p-curriculum_img01@2x.png" alt="ウィンドウのイラスト">
                <p>説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ説明文が入るよ</p>
                <ul class="p-top__curriculumSectionContentCategories">
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculumSectionContentCategoriesItem">
                        <router-link class="c-fs14" to="">HTML</router-link>
                    </li>
                    <li class="p-top__curriculumSectionContentCategoriesItem">
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
        &Section {
            width: 330px;
            padding: 40px;
            margin: 0 auto;
            margin-bottom: 55px;
            background-color: #FFEDE6;
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
                &Categories {
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
            &:nth-child(odd) {
                background-color: #fff;
                border: 2px solid #FFEDE6;
            }
        }
    }
</style>