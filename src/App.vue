<template>
	<v-app>
		<v-main>
			<v-alert :icon="uilShoppingCart"
				>VAlert - icon is passed as a prop</v-alert
			>
			<div>
				<v-icon :icon="uilShoppingCart"></v-icon
				><span> VIcon - icon is passed as a prop</span>
			</div>
		</v-main>
	</v-app>
</template>

<script setup>
	import uilShoppingCart from '~icons/uil/shoppingCart'
</script>
