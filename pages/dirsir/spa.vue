<template>
	<view class="w_container">
		<view class="w_navtab">
			<image src="../../static/back1.png" mode=""></image>
			<text></text>
			<image src="../../static/More.png" mode=""></image>
		</view>
		<view class="banner">
			<image class="bannerImg" src="../../static/icon/休闲娱乐/休闲娱乐_02.png" mode=""></image>
		</view>
		<view class="introduce_con df">
			<view class="introduce_tit">
				玉妙府·日式精油按摩
			</view>
			<view class="introduce_youhui">
				消费赠15%折扣积分
			</view>
		</view>
		<view class="line"></view>
		<view class="spa_time_con">
			<view class="spa_time">
				11:00至凌晨0:00营业 | 共4个房间
			</view>
			<view class="spa_serve df">
				<image src="../../static/icon/休闲娱乐/cheliang.png" mode=""></image>
				<text>免费停车</text>
				<image src="../../static/icon/休闲娱乐/icon-test.png" mode=""></image>
				<text>沐浴房</text>
			</view>
		</view>
		<view class="line"></view>
		<view class="daohang df">
			<image src="../../static/address.png" mode=""></image>
			<text class="w_address">西安市雁塔区丈八沟街道科技四路团结南路中国邮政银行对面</text>
			<view class="w_address_car df">
				<view class="didi">
					打车
				</view>
				<image src="../../static/icon/婚纱摄影/婚纱摄影/打车.png" mode=""></image>
				<image src="../../static/icon/婚纱摄影/婚纱摄影/电话.png" mode=""></image>
			</view>
		</view>
		<view class="line"></view>
		<view class="in_shop">
			<view class="show_con">
				店内环境
			</view>
			<image src="../../static/icon/休闲娱乐/休闲娱乐_12.png" mode=""></image>
		</view>
		<view class="show_img df">
			<image src="../../static/icon/休闲娱乐/休闲娱乐_15.png" mode=""></image>
			<image src="../../static/icon/休闲娱乐/休闲娱乐_17.png" mode=""></image>
			<image src="../../static/icon/休闲娱乐/休闲娱乐_19.png" mode=""></image>
		</view>
		<view class="line"></view>
		<view class="more_pro">
			<view class="more_tit">
				更多产品
			</view>
			<view class="more_phone df">
				<image src="../../static/icon/休闲娱乐/yuyue1.png" mode=""></image>
				<text>请提前电话预约</text>
			</view>
		</view>
		<view class="line"></view>
		<view class="more_spa">
			<view class="more_spa_left">
				<view class="all_time">全身SPA90分钟</view>
				<view class="little_tit">90分钟 | spa养生</view>
			</view>
			<view class="more_spa_right">
				<text class="spa_price">￥599</text>
				<image src="../../static/icon/休闲娱乐/休闲娱乐_29.png" mode=""></image>
			</view>
		</view>
		<view class="line"></view>
		<view class="more_spa">
			<view class="more_spa_left">
				<view class="all_time">全身SPA90分钟</view>
				<view class="little_tit">90分钟 | spa养生</view>
			</view>
			<view class="more_spa_right">
				<text class="spa_price">￥599</text>
				<image src="../../static/icon/休闲娱乐/休闲娱乐_29.png" mode=""></image>
			</view>
		</view>
		<view class="line"></view>
		<view class="more_spa">
			<view class="more_spa_left">
				<view class="all_time">全身SPA90分钟</view>
				<view class="little_tit">90分钟 | spa养生</view>
			</view>
			<view class="more_spa_right">
				<text class="spa_price">￥599</text>
				<image src="../../static/icon/休闲娱乐/休闲娱乐_29.png" mode=""></image>
			</view>
		</view>
		<view class="line"></view>

	</view>
</template>

<script>
</script>

<style>
	page {
		background: #FFFFFF;
	}

	image {
		display: block;
	}

	.df {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
	}

	.w_container {
		width: 100%;
		display: flex;
		flex-direction: column;
		align-items: center;
		position: relative;
	}

	.w_navtab {
		width: 100%;
		height: 100upx;
		background: transparent;
		display: flex;
		justify-content: space-between;
		align-items: center;
		padding: 0 22upx;
		font-weight: 900;
		position: absolute;
		top: 0;
		nav-left: 0;
		z-index: 2;
	}

	.w_navtab image {
		width: 46upx;
		height: 46upx;
	}

	.banner image {
		width: 750upx;
		height: 370upx;
	}

	.introduce_con {
		width: 700upx;
		/* height: 68upx; */
		align-items: center;
		justify-content: space-between;
		margin-top: 20upx;
	}

	.introduce_tit {
		font-size: 38upx;
		font-weight: 900;
	}

	.introduce_youhui {
		width: 180upx;
		height: 44upx;
		line-height: 44upx;
		border-radius: 16upx;
		font-size: 24upx;
		color: #FFFFFF;
		background: #f48a3c;
		margin-left: 70upx;
		text-align: center;
	}

	.spa_time_con {
		width: 700upx;
		height: 100upx;
	}

	.spa_time {
		padding: 0 0 20upx 0;
		font-size: 28upx;
		color: #5f5f5f;
		font-weight: 900;
	}

	.spa_serve {
		justify-content: flex-start;
	}

	.spa_serve image {
		width: 28upx;
		height: 28upx;
	}

	.spa_serve text {
		padding: 0 20upx 0 10upx;
	}

	.line {
		width: 700upx;
		height: 4upx;
		background: #f7f7f7;
		margin: 0 auto;
		margin: 20upx 0;
	}

	.daohang image:first-child {
		margin-top: -45upx;
	}

	.daohang image {
		width: 26upx;
		height: 30upx;
		margin-left: 20upx;
	}

	.w_address {
		width: 512upx;
		margin-right: 10upx;
		height: 100upx;
		line-height: 50upx;
	}

	.w_address_car {
		justify-content: flex-start;
		flex: 1;
		height: 52upx;
		border-left: 4upx solid #DDDDDD;
		position: relative;
	}

	.didi {
		/* width: 48upx; */
		/* height: 27upx; */
		background: #fc9214;
		color: #FFFFFF;
		font-size: 16upx;
		text-align: center;
		position: absolute;
		border-top-right-radius: 14upx;
		border-top-left-radius: 14upx;
		border-bottom-right-radius: 14upx;
		padding: 2upx 4upx;
		z-index: 10;
		top: -16upx;
		right: 80upx;
	}

	.w_address_car image {
		width: 50upx;
		height: 50upx;
		margin: 0 20upx;
	}

	.in_shop {
		display: flex;
		width: 700upx;
		height: 90upx;
		align-items: center;
		/* background: #FFFFFF; */
		/* margin: 10upx 0; */
	}

	.in_shop image {
		width: 28upx;
		height: 30upx
	}

	.show_con {
		width: 100%;
		font-size: 32upx;
		font-weight: 900;
		height: 60upx;
		line-height: 60upx;
		font-size: 30upx;
		border-radius: 5upx;
	}

	.show_img {
		flex-wrap: wrap;
		width: 730upx;
	}

	.show_img image {
		width: 230upx;
		height: 170upx;
		margin: 5upx;
	}

	.active {
		font-size: 28upx;
		font-weight: 900;
		padding-left: 10upx;
	}

	.count text {
		font-size: 20upx;
		color: #aeaeae;
		padding-left: 10upx;
	}

	.more_pro {
		width: 700upx;
		display: flex;
		justify-content: space-between;
		align-items: center;
	}

	.more_tit {
		width: 155upx;
		height: 45upx;
		line-height: 45upx;
		background: #e6610c;
		color: #FFFFFF;
		font-size: 28upx;
		border-radius: 22upx;
		text-align: center;
	}

	.more_phone {
		justify-content: flex-end;
	}

	.more_phone image {
		width: 26upx;
		height: 26upx;
		margin-right: 5upx;
	}

	.more_spa {
		display: flex;
		width: 700upx;
		height: 116upx;
		justify-content: space-between;
		align-items: center;
	}

	.more_spa_right {
		display: flex;
		align-items: center;
	}

	.more_spa_right image {
		width: 123upx;
		height: 56upx;
	}

	.all_time {
		line-height: 50upx;
		font-size: 30upx;
		color: #4f4f4f;
		font-weight: 900;
	}

	.little_tit {
		font-size: 26upx;
		color: #989898;
	}

	.spa_price {
		font-size: 30upx;
		color: #f47c38;
		font-weight: 900;
		margin-right: 5upx;
	}
</style>
