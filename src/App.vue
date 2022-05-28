<template>
	<v-app>
		<v-app-bar
			:collapse="!collapseOnScroll"
			:collapse-on-scroll="collapseOnScroll"
			absolute
			color="deep-purple accent-4"
			dark
			scroll-target="#scrolling-techniques-6"
		>
			<v-app-bar-nav-icon :icon="uilShoppingCart"></v-app-bar-nav-icon>
			<v-avatar color="indigo" :icon="uilShoppingCart"> </v-avatar>
			<v-badge
				:content="messages"
				:value="messages"
				color="green"
				overlap
				:icon="uilShoppingCart"
			>
			</v-badge>
		</v-app-bar>
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
