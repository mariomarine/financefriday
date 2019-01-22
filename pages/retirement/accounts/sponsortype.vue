<template>
  <section class="container">
    <div>
	  <Logo />
      <h2 class="title">
        IRA vs 401k
      </h2>
      <h3 class="subtitle">
        How to choose between an IRA and a 401k
      </h3>
	  <p>
		You don't have to always "choose" between an IRA or a 401k, because you can have both. However, in general, there are reasons to contribute to one before the other.
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

