<template>
	<view class="user">
		<view class="login">
			<image class="img-login" src="../../static/personal_center_04.png"></image>
			<view>请点击登录</view>
		</view>
		<view class="user-a">
			<view class="user-select">
				<image class="icon-a" src="../../static/personal_center_05.png"></image>
				<text class="text">切换小区</text>
			</view>
			<i class="link"></i>
			<view class="user-select">
				<image class="icon-a" src="../../static/personal_center_06.png"></image>
				<text class="text">家庭成员</text>
			</view>
			<i class="link"></i>
			<view class="user-select">
				<image class="icon-a" src="../../static/personal_center_07.png"></image>
				<text class="text">我的收藏</text>
			</view>
		</view>
		<view class="user-a">
			<view class="user-select">
				<image class="icon-a" src="../../static/personal_center_08.png"></image>
				<text class="text">我的钱包</text>
			</view>
			<i class="link"></i>
			<view class="user-select">
				<image class="icon-a" src="../../static/personal_center_09.png"></image>
				<text class="text">优惠卷</text>
			</view>
			<i class="link"></i>
			<view class="user-select">
				<image class="icon-a" src="../../static/personal_center_10.png"></image>
				<text class="text">积分</text>
			</view>
			<i class="link"></i>
			<view class="user-select">
				<image class="icon-a" src="../../static/personal_center_11.png"></image>
				<text class="text">我的订单</text>
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

<style>

.user{
	display: flex;
	flex-direction: column;
	background-color: #F3F5F4;
	height: 100%;
	}
.login{
	width: 100%;
	height: 380rpx;
	text-align: center;
}
.img-login{
	margin-top: 100rpx;
	width: 150rpx;
	height: 150rpx;
	border-radius:75rpx;
	}
.user-a{
	background-color: #FFFFFF;
	display: flex;
	flex-direction: column;
	margin-top: 50rpx;
	width: 100%;
	/* height: 300rpx; */
}
.user-select{
	display: flex;
	width: 100%;
	height: 120rpx;
	flex-direction: row;
	align-items: center;
}	
.link {
    width: 100%;
    height: 1px;
    border-top: solid #F2F2F2 1px;
 }

.icon-a{
	width: 50rpx;
	height: 50rpx;
	padding: 20rpx;
	background-color: #FFFFFF;

}
.text{
	font-size: 35rpx;
}
</style>
