<template>
  <div>
	<h4> Topics </h4>
	<ul>
		<li><nuxt-link to="/retirement" class="green">Retirement</nuxt-link></li>
		<ul>
			<li><nuxt-link to="/retirement/amounts" class="green">Amounts</nuxt-link></li>
			<li><nuxt-link to="/retirement/accounts" class="green">Accounts</nuxt-link></li>
			<ul>
				<li><nuxt-link to="/retirement/accounts/sponsortype" class="green">IRA vs 401k</nuxt-link></li>
				<li><nuxt-link to="/retirement/accounts/accounttype" class="green">Traditional vs Roth</nuxt-link></li>
			</ul>
		</ul>
		<li><nuxt-link to="/taxes" class="green">Taxes</nuxt-link></li>
		<li><nuxt-link to="/assets" class="green">Assets</nuxt-link></li>
			<ul>
				<li><nuxt-link to="/assets/stocks" class="green">Stock Market</nuxt-link></li>
				<li><nuxt-link to="/assets/realestate" class="green">Real Estate</nuxt-link></li>
			</ul>
		<li><nuxt-link to="/insurance" class="green">Insurance</nuxt-link></li>
		<li><nuxt-link to="/referrals" class="green">Referrals</nuxt-link></li>
	</ul>
  </div>
</template>

