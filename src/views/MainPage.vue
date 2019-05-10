<template lang="pug">
	.main-page
		stats
		logo(logo-name="@/assets/images/candy-cane.svg")
		.main-page__boards
			board-container
		.main-page__popular
			popular-threads
</template>
<script>
import Stats from '../components/Stats';
import Logo from '../components/Logo';
import BoardContainer from '../components/BoardContainer';
import PopularThreads from '../components/PopularThreads';

export default {
	components: {
		Stats,
		Logo,
		BoardContainer,
		PopularThreads
	}
}
</script>
