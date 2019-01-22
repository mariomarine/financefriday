<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Retirement
      </h2>
      <h3 class="subtitle">
        Preparing for the Future
      </h3>
	  <p>
		Preparing for Retirement is an important step in your financial journey.
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

