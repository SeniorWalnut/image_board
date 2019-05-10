<template lang="pug">
	.stats
		.stats__users All Users Been There: {{ users }}
		.stats__posts All Posts Been Created: {{ posts }}
		.stats__threads All Threads Been Created: {{ threads }}
</template>
<script>
export default {
	data() {
		return {
			users: null,
			posts: null,
			threads: null
		}
	},

	// created() {
	// 	this.$http.get("main-page/stats")
	// 		.then(data => {
	// 			[this.users, this.posts, this.threads] =  Object.keys(data).map(key => data[key]);
	// 		})
	// }
}
</script>
