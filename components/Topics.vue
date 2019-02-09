<template>
  <div>
	<h4> Topics </h4>
	<ul>
		<li><nuxt-link to="/retirement" class="important">Retirement</nuxt-link></li>
		<ul>
			<li><nuxt-link to="/retirement/amounts" class="important">Amounts</nuxt-link></li>
			<li><nuxt-link to="/retirement/accounts" class="important">Accounts</nuxt-link></li>
			<ul>
				<li><nuxt-link to="/retirement/accounts/sponsortype" class="important">IRA vs 401k</nuxt-link></li>
				<li><nuxt-link to="/retirement/accounts/accounttype" class="important">Traditional vs Roth</nuxt-link></li>
				<li><nuxt-link to="/retirement/accounts/hsa" class="trivial">HSA (Health Savings Account)</nuxt-link></li>
				<li><nuxt-link to="/retirement/accounts/solok" class="trivial">Individual 401k (Solo-K)</nuxt-link></li>
				<li><nuxt-link to="/retirement/accounts/selfdirected" class="nerdy">Self-Directed IRA</nuxt-link></li>
			</ul>
			<li><nuxt-link to="/retirement/accounts" class="trivial">F.I.R.E</nuxt-link></li>
		</ul>
		<li><nuxt-link to="/taxes" class="important">Taxes</nuxt-link></li>
			<ul>
				<li><nuxt-link to="/taxes/creditvsdeduction" class="important">Tax Credit vs Tax Deduction</nuxt-link></li>
				<li><nuxt-link to="/taxes/brackets" class="important">Tax Brackets</nuxt-link></li>
				<li><nuxt-link to="/taxes/savers" class="important">Tax Saver's Credit</nuxt-link></li>
			</ul>
		<li><nuxt-link to="/assets" class="important">Assets</nuxt-link></li>
			<ul>
				<li><nuxt-link to="/assets/stocks" class="important">Stock Market</nuxt-link></li>
				<ul>
					<li><nuxt-link to="/assets/stocks/funds" class="important">Funds</nuxt-link></li>
					<ul>
						<li><nuxt-link to="/assets/stocks/funds/mutual" class="important">Mutual Funds</nuxt-link></li>
						<li><nuxt-link to="/assets/stocks/funds/etf" class="important">ETFs (Exchange-Traded Funds)</nuxt-link></li>
						<li><nuxt-link to="/assets/stocks/funds/reit" class="trivial">REITs (Real Estate Investment Trusts)</nuxt-link></li>
						<li><nuxt-link to="/assets/stocks/funds/cef" class="trivial">CEFs (Closed-End Funds)</nuxt-link></li>
					</ul>
				</ul>
				<li><nuxt-link to="/assets/realestate" class="important">Real Estate</nuxt-link></li>
			</ul>
		<li><nuxt-link to="/insurance" class="important">Insurance</nuxt-link></li>
		<li><nuxt-link to="/referrals" class="important">Referrals</nuxt-link></li>
	</ul>
  </div>
</template>

