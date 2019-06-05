<template>
	<view class="content">
		<image class="logo" src="/static/logo.png"></image>
		<div class="icon">&#xe60d;&#xe608;&#xe64d;&#xe614;</div>
		<view>
			<text class="title">{{title}}哈哈哈</text>
		</view>
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

		}
	}
</script>

<style>
	@font-face {
		font-family: testicon;
		src: url('~@/static/icon/iconfont.ttf');
	}

	.content {
		text-align: center;
		height: 400upx;
	}

	.icon {
		font-family: testicon;
	}

	.logo {
		height: 200upx;
		width: 200upx;
		margin-top: 200upx;
	}

	.title {
		font-size: 36upx;
		color: #8f8f94;
	}
</style>
