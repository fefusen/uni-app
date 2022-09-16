<template>
	<view>
		<text>{{inerData}}</text>
		<br>
		<text>父组件传值为：{{value}}</text>
	</view>
</template>

<script>
	export default {
		name: "customerComponent",
		props: {
			value: {
				type: String,
				default: ''
			}
		},
		data() {
			return {
				inerData: '我是自定义组件'
			};
		}
	}
</script>

<style lang="less">

</style>
