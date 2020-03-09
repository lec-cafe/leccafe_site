<template>
    <div>
        <div class="p-container">
            <DefaultHeader />
            <TopHeading />
            <TopMerit />
            <TopCurriculum />
            <TopReason />
            <TopAccess />
            <TopJoin />
        </div>
    </div>
</template>

<script>
    import DefaultHeader from "~/components/layout/header/DefaultHeader.vue";
    import TopHeading from "~/components/TopHeading.vue"
    import TopMerit from "~/components/TopMerit.vue"
    import TopCurriculum from "~/components/TopCurriculum.vue"
    import TopReason from "~/components/TopReason.vue"
    import TopAccess from "~/components/TopAccess.vue"
    import TopJoin from "~/components/TopJoin.vue"

    export default {
        name: "index",
        components: {
            DefaultHeader,
            TopHeading,
            TopMerit,
            TopCurriculum,
            TopReason,
            TopAccess,
            TopJoin
        }
    }
</script>

<style lang="scss" scoped>
    @import "../assets/scss/mixins/container.scss";
    @import "../assets/scss/component/button.scss";
    .p-container {
        @include container();
    }
    p {
        font-size: 14px;
    }
    .p-top__titles {
        text-align: center;
        margin: 40px auto;
        font-size: 40px;
    }
</style>