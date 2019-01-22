<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        Retirement Accounts
      </h2>
      <h3 class="subtitle">
        Where to Save for the Future
      </h3>
	  <p>
		Choosing who to entrust with your money, and the type of account to choose, can be a complicated process. Let's make it simpler.
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

