<script lang="ts">
	//svelte
	import { onMount } from 'svelte';
	import Footer from '$lib/footer/footer.svelte';
	onMount(() => {});
</script>

<main class="overflow-y-auto w-full h-full flex flex-col items-center">
	<div class="pt-4 px-4 w-full flex justify-center">
		<div class="w-full max-w-[1280px]">
			<h1>Webplayground How To Use</h1>
			<hr />
		</div>
	</div>

	<div class="pt-4 px-4 min-h-[320px] w-full flex justify-center">
		<div class="w-full max-w-[1280px]">
			<h2 class="mb-2">Chapter title</h2>
			<br/>
			<p>The AI hasn't figure out the next word to generate yet.</p>
		</div>
	</div>
	<div class="flex-grow" />

	<hr class="w-full" />
	<div class="w-full px-4">
		<Footer className="w-full max-w-[1280px]" />
	</div>
</main>

<style>
</style>
