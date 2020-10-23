<template>
	<!-- <view class="container log-list">
	  <block v:for="{{logs}}" wx:for-item="log">
	    <text class="log-item">{{index + 1}}. {{log}}</text>
	  </block>
	</view> -->
</template>

<script>
	
	export default {
		data() {
			return {
				
			};
		}
	}
</script>

<style lang="scss">
	.log-list {
	  display: flex;
	  flex-direction: column;
	  padding: 40rpx;
	}
	.log-item {
	  margin: 10rpx;
	}

</style>
