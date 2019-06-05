<script>
	export default {
		onLaunch: function() {
			console.log('App Launch')
			console.log(process.env.NODE_ENV)
			// #ifdef APP-PLUS
			var appid = plus.runtime.appid;
			console.log('应用的 appid 为：' + appid);
			// #endif
			console.log(Window)
			switch (uni.getSystemInfoSync().platform) {
				case 'android':
					console.log('运行在Android上')
					break;
				default:
					console.log('运行在开发者工具上')
					break;
			}
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
</style>
