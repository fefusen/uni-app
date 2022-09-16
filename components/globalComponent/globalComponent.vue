<template>
	<view>
		<text>{{inerData}}</text>
		<br>
		<text>父组件传值为：{{value}}</text>
	</view>
</template>

<script>
	export default {
		name:"globalComponent",
		props: {
			value: {
				type: String,
				default: ''
			}
		},
		data() {
			return {
				inerData: '我是全局组件'
			};
		}
	}
</script>

<style lang="less">

</style>