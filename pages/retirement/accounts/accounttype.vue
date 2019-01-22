<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Roth vs Traditional
      </h2>
      <h3 class="subtitle">
        Choosing to pay taxes now or later
      </h3>
	  <p>
		Depending on your situation, you may choose Roth or Traditional (or probably both).
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

