<template>
  <div>
	<slot name="link"></slot>
	<p>Account Types:</p>
	<ul>
		<li v-for="type in types" v-bind:key="type" v-bind:type="type"> {{type}} </li>
	</ul>
	<slot name="bonus"></slot>
	<slot name="specials"></slot>
	<slot name="review"></slot>
  </div>
</template>

<script>
export default {
  props: ['types']
}
</script>

