<template>
	<BasePage>
		<div slot="content">
			<h2 class="title">
				IRA vs 401k
			</h2>
			<h3 class="subtitle">
				How to choose between an IRA and a 401k
			</h3>
			<p>
				You don't have to always "choose" between an IRA or a 401k, because you can have both. However, in general, there are reasons to contribute to one before the other.
			</p>
			<p>
				My recommended order (90% of the time) is:
				<ol>
					<li>
						Contribute enough to get the full employer match in 401k. (This is free money, which is usually better than quibbling about when to pay taxes)
					</li>
					<li>
						Max out your Roth IRA.
					</li>
					<li>
						Finish your 401k contributions.
					</li>
					<li>
						Invest in some other form of TSA (Tax Sheltered Account), such as an <nuxt-link to="/retirement/accounts/hsa">HSA</nuxt-link>, Real Estate, Whole Life Insurance, etc...
					</li>
				</ol>
			</p>
		</div>
	</BasePage>
</template>

<script>
import BasePage from '~/components/BasePage.vue'

export default {
	components: {
		BasePage
	}
}
</script>

