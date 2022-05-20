<template>
	<v-app>
		<v-main>
			<i-uil-android />
			<v-alert :icon="uilShoppingCart"
				>VAlert - icon is passed as a prop</v-alert
			>
		</v-main>
	</v-app>
</template>

<script setup>
	import uilShoppingCart from '~icons/uil/shoppingCart'
</script>
