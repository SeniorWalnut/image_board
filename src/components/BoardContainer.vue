<template lang="pug">
	.board-container
		main-link(
			v-for="(link, ind) in links",
			:key="link + ind" 
		)
</template>
<script>
import MainLink from './MainLink';

export default {
	components: { MainLink },
	props: {
		links: {
			type: Array,
			default:() => []
		}
	}
}
</script>