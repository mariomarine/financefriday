<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Retirement Amounts
      </h2>
      <h3 class="subtitle">
        How much do you need for Retirement?
      </h3>
	  <p>
		How much do you actually need to retire?
	  </p>
	  <Topics />
    </div>
  </section>
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

