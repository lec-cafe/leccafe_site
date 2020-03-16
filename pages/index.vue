<template>
    <div>
        <DefaultHeader />
        <div class="p-container">
            <TopHeading />
            <TopMerit />
            <TopCurriculum />
            <TopReason />
            <TopAccess />
            <TopJoin />
            <DefaultFooter />
        </div>
    </div>
</template>

<script>
    import DefaultHeader from "~/components/layout/header/DefaultHeader.vue";
    import TopHeading from "~/pages/-TopHeading.vue"
    import TopMerit from "~/pages/-TopMerit.vue"
    import TopCurriculum from "~/pages/-TopCurriculum.vue"
    import TopReason from "~/pages/-TopReason.vue"
    import TopAccess from "~/pages/-TopAccess.vue"
    import TopJoin from "~/pages/-TopJoin.vue"
    import DefaultFooter from "~/components/layout/footer/DefaultFooter.vue";

    export default {
        components: {
            DefaultHeader,
            TopHeading,
            TopMerit,
            TopCurriculum,
            TopReason,
            TopAccess,
            TopJoin,
            DefaultFooter
        }
    }
</script>

<style lang="scss" scoped>
    @import "../assets/scss/mixins/container.scss";
    @import "../assets/scss/component/button.scss";
    .p-container {
        @include container();
    }
</style>