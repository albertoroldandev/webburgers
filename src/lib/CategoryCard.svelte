<script>
	let { category } = $props();
</script>

<li class="select-none relative border-2 rounded-xl border-zinc-200 w-[500px] h-[200px] p-6 cursor-pointer transition-colors duration-100 hover:bg-zinc-100 active:bg-zinc-200">
	<h3 class="text-3xl font-inter font-bold">{category.name}</h3>
	<img class="no-drag absolute bottom-2 right-2" src={category.image} alt="Burger" width="150px">
</li>