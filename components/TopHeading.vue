<template>
	<div class="p-top__heading">
		<div class="p-top__heading__title">
			<img src="~/assets/images/leccafe_logo.svg" alt="">
			<hr class="p-top__headingHr" width="160px" color="#E15F52" noshade>
			<h2 class="c-fs18 c-fwBold">手軽に始める<br><br>プログラミング<br><br>スクール</h2>
		</div>
		<div class="p-top_heading--1 c-mb20">
			<img class="p-top_headingImage c-mb20" src="~/assets/images/p-hero_img01@2x.png" alt="">
			<p class="c-mb20">Lec Cafeは学生や社会人を対象とした<br>大阪のプログラミングスクールです。</p>
		</div>
		<div class="p-top_heading__buttons c-mb40">
			<router-link class="c-buttonWhite c-fs20 c-fwBold" to="">資料請求</router-link>
			<router-link class="c-buttonRed c-fs20 c-fwBold" to="">申し込み</router-link>
		</div>
	</div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
	.p-top__heading {
		padding-top: 30px;
		&__title {
			img {
				width: 200px;
				height: 46px;
			}
		}
	}
	.p-top__headingHr {
		margin: 30px 0 20px 0;
		height: 2px;
    }
    .p-top_heading--1 {
        text-align: right;
		position: relative;
		top: -45px;
		p {
			text-align: left;
		}
    }
    .p-top_headingImage {
        width: 320px;
		height: 250px;
    }
    .p-top_heading__buttons {
        display: flex;
		justify-content: space-around;
		position: relative;
		top: -45px;
		a {
			width: 160px;
			height: 50px;
		}
    }

</style>