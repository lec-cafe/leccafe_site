<template>
    <div>
        <div class="l-footer">
            <ul class="l-footer__menus">
                <li class="l-footer__menusItem">
                    <router-link to="">メリット</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link to="">カリキュラム</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link to="">選ばれる理由</router-link>
                </li>
                <li class="l-footer__menusItem">
                    <router-link to="">アクセス</router-link>
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
    .l-footer {
        width: 275px;
        height: 380px;
        margin: 50px auto;
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
            height: 26px;
            margin-bottom: 48px;
        }
    }
</style>