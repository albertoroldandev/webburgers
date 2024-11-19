<script>
	import CategoryList from './lib/CategoryList.svelte'
</script>

<header class="flex flex-col justify-center items-center py-10">
	<h1 class="select-none text-6xl text-yellow-400 font-marhey">W</h1>
</header>

<CategoryList />

<footer class="flex flex-col justify-center py-10 gap-8">
	<div class="flex flex-row justify-between items-center select-none">
		<button class="bg-white px-6 py-4 border-2 rounded-xl border-zinc-300 transition-colors duration-100 hover:bg-zinc-100 active:bg-zinc-200">Cancelar pedido</button>
	<div class="flex flex-row justify-center items-center gap-6">
		<div class="relative p-2">
			<img class="no-drag" src="/webburgers/paper-bag.svg" alt="Paper bag icon" width="40px">
			<span class="absolute top-0 right-0 bg-red-600 w-5 rounded-3xl text-center font-semibold text-sm text-white">3</span>
		</div>
		<span class="text-2xl font-extrabold text-zinc-700">€0,00</span>
	</div>
	<button class="bg-yellow-300 px-6 py-4 border-2 rounded-xl border-yellow-500 transition-colors duration-100 hover:bg-yellow-400 active:bg-yellow-500">Revisar y pagar mi pedido</button>
	</div>
	<p class="text-center text-xs">This project was created by <span class="font-bold">Alberto Roldán</span> for educational purposes and is not affiliated with, endorsed by, or related to any fast food chain.</p>
</footer>


