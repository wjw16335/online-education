<template>
	<view class="my-page">
		<view class="my-page">
			<view class="my-header">
				<view class="header-content">
					<view class="buld">
					</view>
					<view class="right" >
						<text >立即登录</text>
						<text style="margin-top:70rpx;margin-left:-160rpx;font-size: 15rpx;">登录后解锁更多功能</text>
					</view>
				</view>
				
			</view>
		</view>
	</view>
</template>
<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>
<style lang="scss">
	.my-page {
		.my-header {
			.header-content {
				height: 200rpx;
				padding: 50rpx 39rpx;
				background-color: #5ccc84;
				border-radius: 0 0 30px 30px;

				.buld {
					background-color: white;
					width: 120rpx;
					height: 120rpx;
					border-radius: 50%;
				}

				.right {
					color: white;
					margin-top: -130rpx;
					margin-left: 170rpx;
					font-size: 40rpx;
					display: flex;
				}
			}

			// .order {
			// 	height: 140rpx;
			// 	background-color: #ffffff;
			// 	display: flex;
			// 	width: 90%;
			// 	background-color: white;
			// 	margin-top: -100rpx;
			// 	margin-left: 40rpx;
			// 	justify-content: space-around;
			// 	border-radius: 10rpx;
			// 	box-shadow: 2px 2px 3px darkgray;

			// 	.yi {
			// 		margin-top: 30rpx;
			// 		text-align: center;
			// 		.size{
			// 			font-size: 12px;
			// 			margin-top: 10rpx;
			// 			color: #6c757d;
			// 		}
			// 	}
			// }
		}
	}
</style>
