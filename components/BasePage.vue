<template>
	<div>
		<Logo />
		<slot name="content"></slot>
		<Topics />
	</div>
</template>

<script>
import Topics from '~/components/Topics.vue'
import Logo from '~/components/Logo.vue'

export default {
	components: {
		Topics,
		Logo
	}
}
</script>

