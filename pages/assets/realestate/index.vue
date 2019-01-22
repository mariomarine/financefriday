<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Asset: Real Estate
      </h2>
      <h3 class="subtitle">
        Why so many investors prefer Real Estate
      </h3>
	  <p>
		Real Estate is one of the oldest forms of investing, for good reason.
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

