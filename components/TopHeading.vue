<template>
	<div class="p-top__heading">
		<div>
			<h1>lec café</h1>
			<hr class="p-top__headingHr" width="100px" color="#E15F52" noshade>
			<h2 class="c-fs20">手軽に始める<br>プログラミング<br>スクール</h2>
		</div>
		<div class="p-top_heading--1 c-mb20">
			<img class="p-top_headingImage" src="~/assets/images/top_img1.jpg" alt="">
			<p>Lec Cafeは学生や社会人を対象とした<br>大阪のプログラミングスクールです。</p>
		</div>
		<div class="p-top_heading__buttons c-mb40">
			<router-link class="c-buttonWhite c-fs20" to="">資料請求</router-link>
			<router-link class="c-buttonRed c-fs20" to="">申し込み</router-link>
		</div>
	</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
	.p-top__headingHr {
        margin: 10px 0;
    }
    .p-top_heading--1 {
        text-align: right;
    }
    .p-top_headingImage {
        width: 290px;
        height: 230px;
    }
    .p-top_heading__buttons {
        display: flex;
        justify-content: space-around;
    }

</style>