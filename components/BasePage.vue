<template>
	<div>
		<Logo />
		<slot name="content"></slot>
		<Topics />
		<Legend />
	</div>
</template>

<script>
import Topics from '~/components/Topics.vue'
import Legend from '~/components/Legend.vue'
import Logo from '~/components/Logo.vue'

export default {
	components: {
		Topics,
		Legend,
		Logo
	}
}
</script>

