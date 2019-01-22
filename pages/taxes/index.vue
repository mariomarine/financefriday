<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Taxes
      </h2>
      <h3 class="subtitle">
        Understanding how the system works for you.
      </h3>
	  <p>
		As "Famous Person" once said, "There are only two things certain in life: Death and Taxes."
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

