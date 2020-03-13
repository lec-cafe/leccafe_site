<template>
	<div class="p-top__heading">
		<div class="p-top__headingTitle">
			<img src="~/assets/images/leccafe_logo.svg" alt="">
			<hr class="p-top__headingTitleHeadingHr">
			<h2 class="c-fs18 c-fwBold">手軽に始める<br><br>プログラミング<br><br>スクール</h2>
		</div>
		<div class="p-top__headingDescription">
			<img class="p-top__headingDescriptionImage" src="~/assets/images/p-hero_img01@2x.png" alt="">
			<p class="c-mb20">Lec Cafeは学生や社会人を対象とした<br>大阪のプログラミングスクールです。</p>
		</div>
		<div class="p-top__headingDescriptionButtons">
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
		padding: 30px 20px 0;
		&Title {
			&HeadingHr {
				margin: 30px 0 20px 0;
				height: 1px;
				width: 160px;
				background-color: #E15F52;
			}
			img {
				width: 200px;
				height: 46px;
			}
		}
		&Description {
			text-align: right;
			position: relative;
			top: -45px;
			margin-bottom: 20px;
			p {
				text-align: left;
			}
			&Image {
				width: 320px;
				height: 250px;
				margin-bottom: 20px;
			}
			&Buttons {
				display: flex;
				justify-content: space-around;
				position: relative;
				top: -45px;
				a {
					width: 160px;
					height: 50px;
				}
			}
		}
	}
</style>
