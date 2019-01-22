<template>
  <section class="container">
    <div>
	  <Logo />
      <h3 class="subtitle">
        Learn about Finances
      </h3>
	  <p>
		Welcome to Ryan's site! This is where I will compile all the information I have to help you find your cadence to becoming financially familiar.
	  </p>
	  <p>
		Disclaimer: I am not a financial professional, please consult with a CPA/Financial Advisor/other professional
		before making any personal decisions with your money.
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

