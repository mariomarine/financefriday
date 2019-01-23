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
					<li>
						<Review :types="['Taxable','IRA']">
							<a slot="link" href="https://wlth.fr/2ixluVC" class="external"> Wealthfront </a>
							<p slot="bonus"> We both get an additional $5000 managed free. </p>
							<ul slot="review">
								<li> Wealthfront is a Robo-Advisor, this means it automatically invests according to your risk tolerance and is very good at it. </li>
								<li> Wealthfront has a very simple and clean interface. </li>
								<li> The fees are just a little high...but with the referral link there is little risk since the first $5000 is managed for free. </li>
							</ul>
						</Review>
					</li>
					<li>
						<Review :types="['Taxable','IRA']">
							<a slot="link" href="https://www.schwab.com/public/schwab/nn/promo/refer-prospect.html?refrid=REFERNCG498N4" class="external"> Charles Schwab </a>
							<p slot="bonus"> You get $100 when you open an account with $1000 or more. </p>
							<ul slot="review">
								<li> The referral bonus is rather large. </li>
								<li> The interface is...alright, comprehensive, but not amazing. </li>
								<li> There is a wide variety of options available (both investable securities and account types). </li>
							</ul>
						</Review>
					</li>
					<li>
						<Review :types="['Taxable']">
							<a slot="link" href="https://share.robinhood.com/ryanb551" class="external"> Robinhood </a>
							<p slot="bonus"> We both get a free random stock (probably valued around $5, could be as high as about $200) </p>
							<ul slot="review">
								<li> Robinhood is "free", as they charge no commission, nor do they have annual fees. </li>
								<li> Robinhood has grown faster than almost every other brokerage, and has become quite a powerhouse, it has a great interface. </li>
								<li> There is a Robinhood Gold feature that can be a benefit for a large enough investor. </li>
							</ul>
						</Review>
					</li>
					<li>
						<Review :types="['Analysis']">
							<a slot="link" href="https://share.personalcapital.com/x/0LriAP" class="external"> Personal Capital </a>
							<p slot="bonus"> We both get a $20 Amazon Gift Card when you sign up and link lots of accounts (look at details before counting on it). </p>
							<ul slot="review">
								<li> Personal Capital is free, it makes it's money from selling money management services to larger investors. </li>
								<li> If you have ever wanted to see a little more data around your investments, this is a great place to go. </li>
								<li> This is an account aggregator, so it works best if you link all of your accounts. </li>
								<li> Also, this is my preferred way to track my Net Worth, which is an important metric into self-financial-insight. </li>
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
import Review from '~/components/Review.vue'

export default {
	components: {
		BasePage,
		Review
	}
}
</script>

