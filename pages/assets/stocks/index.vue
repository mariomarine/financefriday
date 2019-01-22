<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Asset: Stock Market
      </h2>
      <h3 class="subtitle">
		What owning stocks mean, and how it benefits you.
      </h3>
	  <p>
        Arguably the most mainstream choice for investing. 
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

