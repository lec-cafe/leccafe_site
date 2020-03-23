<template>
    <div>
        <div class="l-footer">
            <ul class="l-footer__menus">
                <li class="l-footer__menusItem">
                    <router-link v-scroll-to="'#anchorMerit'" to>メリット</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link v-scroll-to="'#anchorCurriculum'" to>カリキュラム</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link v-scroll-to="'#anchorReason'" to>選ばれる理由</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link v-scroll-to="'#anchorAccess'" to>アクセス</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link to="">資料請求</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link to="">申し込み</router-link>
                </li>
            </ul>
            <hr class="l-footer__hr">
            <img class="l-footer__logo" src="~/assets/images/leccafe_logo.svg" alt="lec cafeロゴ">
            <p class="c-fs14">© 2020 Lec Café inc.</p>
        </div>
    </div>
</template>

<script>
    export default {
    }
</script>

<style lang="scss" scoped>
@import "~/assets/scss/mixins/container.scss";

    .l-footer {
        @include container();
        width: 275px;
        text-align: center;
        &__menus {
            padding: 0;
        }
        &__menusItem {
            list-style: none;
            margin-bottom: 30px;
        }
        &__menusItem a {
            color:#E15F52;
            font-weight: bold;
            font-size: 14px;
        }
        &__hr {
            height: 2px;
            background-color: #E15F52;
            border: none;
        }
        &__logo {
            width: 120px;
            height: auto;
            margin-bottom: 48px;
        }
    }

    @media screen and (min-width: 768px) {
        .l-footer {
            width: 728px;
        }
    }
</style>