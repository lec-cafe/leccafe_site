<template>
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
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>
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
</style>