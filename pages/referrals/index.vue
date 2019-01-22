<template>
	<BasePage>
		<div slot="content">
			<h2 class="title">
				Referral Links
			</h2>
			<h3 class="subtitle">
				Links that give referral bonuses to either/both parties
			</h3>
			<ul>
				<li>Stocks</li>
				<ul>
					<li>
						<Review :types="['Taxable','IRA']">
							<a slot="link" href="http://mbsy.co/llmZT" class="external"> M1 Finance </a>
							<p slot="bonus"> We both get $10 when you deposit $100. </p>
							<p slot="special"> They are running an additional special until the end of January 2019, open an IRA with $500 and recieve $25. </p>
							<ul slot="review">
								<li> M1 Finance is "free", as they charge no commission, nor do they have annual fees. </li>
								<li> M1's ability to buy fractional shares is a huge boon to the small investor. </li>
								<li>
									Instead of buying shares by number, you create "Pies", which are meant to be comprised of the percentages you want each of your stocks/funds to have in your portfolio.
									It is also worth noting that you can still buy shares in dollar amounts.
								</li>
								<li> The interface is intuitive and easy to understand. </li>
								<li>
									The M1 Borrow feature can be a great feature if you are interested in using leverage. Accounts with a balance >$10,000 can borrow up to 35% of the portfolio balance.
									They do not run a credit check, and therefore can be a great way to increase your available capital.
								</li>
							</ul>
						</Review>
					</li>
				</ul>
			</ul>
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

