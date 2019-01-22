<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Assets
      </h2>
      <h3 class="subtitle">
        What vehicles are available for you to invest in?
      </h3>
	  <p>
		There are many options for Asset classes you can invest in.
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

