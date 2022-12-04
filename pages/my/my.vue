<template>
	<view>
		<list></list>
		<login></login>
		<favour></favour>
	</view>
</template>

<script>
	import list from '@/pages/my/components/list.vue'
	import login from '@/pages/my/components/login.vue'
	import favour from '@/pages/my/components/favour.vue'
	export default {
		data() {
			return {

			};
		},
		components: {
			list,
			login,
			favour
		}
	}
</script>

<style lang="scss">

</style>
