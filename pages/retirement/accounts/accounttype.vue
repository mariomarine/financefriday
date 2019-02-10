<template>
	<BasePage>
		<div slot="content">
			<h2 class="title">
				Roth vs Traditional
			</h2>
			<h3 class="subtitle">
				Choosing to pay taxes now or later
			</h3>
			<p>
				Depending on your situation, you may choose Roth or Traditional (or probably both).
			</p>
			<p>
				The simple explanation is:
				<ul>
					<li>
						If you expect to live on more money than you are making now, choose Roth
					</li>
					<li>
						If you expect to be spending less when you retire than you are now, choose Traditional.
					</li>
				</ul>
				Personally, I expect to be spending quite a bit more during retirement (think medical expenses, spoiling grandkids, traveling, etc...), so I max out my Roth Contributions first.
			</p>
			<p>
				However, if you go the Roth route, be aware that you will still have tax deductions when you retire, and if you have no taxable income (aka traditional contributions), you will be giving up some free taxes. So contributing at least a little to a traditional retirement account is often more beneficial than choosing Roth only...
			</p>
			<h3>
				External Links
			</h3>
			<p>
				Here are some extra links to help with your decision:
			</p>
			<extLink>
				<img alt="NerdWallet Logo" src="~/assets/images/nerdwallet_logo.png" slot="logo" />
				<h4 slot="header">
					<a class="external" href="https://www.nerdwallet.com/article/roth-or-traditional-ira-account"> Roth IRA vs Traditional IRA </a>
				</h4>
				<p slot="excerpt"> The two main types of IRAs differ mainly in how and when your money is taxed. But several features make the Roth a better choice for most eligible retirement savers. </p>
			</extLink>
			<extLink>
				<img alt="Investor's Business Daily Logo" src="~/assets/images/investors_business_daily_logo.png" slot="logo" />
				<h4 slot="header">
					<a class="external" href="https://www.investors.com/etfs-and-funds/retirement/how-to-choose-between-roth-traditional-ira-401k"> Roth IRA Vs. Traditional IRA, 401(k): Which Is Better For You? </a>
				</h4>
				<p slot="excerpt"> Roth IRA vs. traditional IRA: how can you choose one or the other? What's the difference? Ditto for Roth 401(k) accounts and traditional 401(k) accounts. And, more importantly, which one is best for you? </p>
			</extLink>
		</div>
	</BasePage>
</template>

<script>
import BasePage from '~/components/BasePage.vue'
import extLink from '~/components/extLink.vue'

export default {
	components: {
		BasePage,
		extLink
	}
}
</script>

