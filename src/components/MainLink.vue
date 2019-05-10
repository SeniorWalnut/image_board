<template lang="pug">
	a.main-link(:href="link")
</template>
<script>
export default {
	props: {
		link: {
			type: String,
			default: '#'
		} 
	}
}
</script>