<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Insurance
      </h2>
      <h3 class="subtitle">
        Protecting yourself from undue risk
      </h3>
	  <p>
		Let's look at when insurance is useful, and why it is an important aspect of your financial life.
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

