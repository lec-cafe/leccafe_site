<template>
    <div>
        <div class="p-container">
            <div class="p-top">
                <DefaultHeader />
                <TopHeading />
                <TopMerit />
                <TopCurriculum />
                <TopReason />
                <TopAccess />
                <TopJoin />
            </div>
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

    export default {
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
</style>