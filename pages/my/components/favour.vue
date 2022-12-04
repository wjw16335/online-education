<template>
	<view class="foot">
		<view class="box">
			<view class="box-item">
				<view class="iconfont icon-9 mr-2" style="font-size: 50rpx;color:#95c4f4;"></view>
				<view class="size">我的优惠劵</view>
			</view>
			<view class="iconfont icon-jinru"></view>
		</view>
		<view class="box">
			<view class="box-item">
				<view class="iconfont icon-help mr-2" style="font-size: 50rpx;color:#95c4f4;"></view>
				<view class="size">常见问题</view>
			</view>
			<view class="iconfont icon-jinru"></view>
		</view>
		<view class="box">
			<view class="box-item">
				<view class="iconfont icon-leimupinleifenleileibie mr-2" style="font-size: 50rpx;color:#95c4f4;"></view>
				<view class="size">设置</view>
			</view>
			<view class="iconfont icon-jinru"></view>
		</view>

	</view>
</template>
<script>
</script>

<style lang="scss">
	.foot {
		width: 100%;
		margin-top: 30rpx;

		.box {
			width: 85%;
			height: 100rpx;
			padding-left: 60rpx;
			border-bottom: 1px solid gainsboro;
			line-height: 80rpx;
			display: flex;
			align-items: center;
			justify-content: space-between;
		}

		.box-item {
			display: flex;
			align-items: center;
			justify-content: space-between;
			.size{
				font-size: 28rpx;
			}
		}
	}
</style>
