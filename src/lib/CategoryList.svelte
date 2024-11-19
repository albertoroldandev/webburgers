<script>
	import CategoryCard from './CategoryCard.svelte';

	const categories = [
		{
			name: 'Hamburguesas',
			image: '/webburgers/images/products/burger-mega.webp'
		},
		{
			name: 'Complementos',
			image: '/webburgers/images/products/sides-bacon-cheese-fries-big.webp'
		},
		{
			name: 'Postres',
			image: '/webburgers/images/products/desserts-frosty-chocolate.webp'
		},
		{
			name: 'Bebidas',
			image: '/webburgers/images/products/drinks-cola.webp'
		}
	]
</script>

<section>
	<h2 class="text-5xl font-inter font-bold mb-12">Descubre nuestro menú</h2>
	<ul class="flex justify-center gap-4 flex-wrap">
	{#each categories as category}
		<CategoryCard {category} />
	{/each}
	</ul>
</section>