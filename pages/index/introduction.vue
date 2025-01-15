<template>
	<view class="content">
		<u--text bold size="19" text="介绍"></u--text>
		<view class="introduction-content">
			<u--text size="15" :text="introductionContent1"></u--text>
		</view>
		<view class="introduction-content">
			<u--text size="15" :text="introductionContent2"></u--text>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				introductionContent1: "🤗欢迎使用无痕去水印小程序🤗 ",
				introductionContent2: "🤗小程序每天赠送免费解析次数，需要更多次数可咨询客服🤗",
				
			}
		}
	}
</script>

<style lang="scss">
	page {
		background-color: $u-bg-color;
	}

	.content {
		padding: 20rpx 20rpx 0 20rpx;
	}

	.introduction-content {
		padding-top: 5rpx;
		padding-bottom: 5rpx;
		text-indent: 2em;
	}
</style>