<main class="grid grid-rows-[1fr_auto]">
<div class="bg-blue-500 p-4 overflow-y-auto">
	{#each Array.from({ length: 1000 }, (_, i) => i) as item}
		<div>
			{item}
		</div>
	{/each}
</div>
<footer class="bg-green-500 p-4">(footer)</footer>
</main>
