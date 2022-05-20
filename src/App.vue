<template>
	<v-app>
		<v-main>
			<i-uil-android />
			<!-- <v-alert :icon="uilShoppingCart"
				>VAlert - icon is passed as a prop</v-alert
			> -->
			<br />
			<v-alert>
				<template #default> VAlert - icon is passed on #append1 slot </template>
				<template #append>
					<i-uil-shopping-cart />
				</template>
			</v-alert>
			<br />
			<v-alert>
				<template #default> VAlert - icon is passed on #append2 slot </template>
				<template #append>
					<i
						class="v-icon notranslate v-icon--size-default v-theme--light"
						aria-hidden="true"
					>
						<i-uil-shopping-cart />
					</i>
				</template>
			</v-alert>
			<br />
			<v-alert>
				<template #default> VAlert - icon is passed #prepend1 slot </template>
				<template #prepend>
					<i-uil-shopping-cart />
				</template>
			</v-alert>
			<br />
			<v-alert>
				<template #default> VAlert - icon is passed #prepend2 slot </template>
				<template #prepend>
					<i
						class="v-icon notranslate v-icon--size-default v-theme--light"
						aria-hidden="true"
					>
						<i-uil-shopping-cart />
					</i>
				</template>
			</v-alert>
		</v-main>
	</v-app>
</template>

<script setup>
	// import uilShoppingCart from '~icons/uil/shoppingCart';
</script>
