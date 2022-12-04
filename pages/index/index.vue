<template>
	<view class="content">
		<view class="iconfont icon-tijiao">提交</view>
		<view class="bg-main-hover font-lg animated bounce text-center animate__animated animate__flipInX">
			12346
		</view>
		<view class="bg-main-hover font-lg animated bounce text-center animate__animated animate__flip">翻转</view>
		<login></login>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		},
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}

	.logo {
		height: 200rpx;
		width: 200rpx;
		margin-top: 200rpx;
		margin-left: auto;
		margin-right: auto;
		margin-bottom: 50rpx;
	}

	.text-area {
		display: flex;
		justify-content: center;
	}

	.title {
		font-size: 36rpx;
		color: #8f8f94;
	}
</style>
