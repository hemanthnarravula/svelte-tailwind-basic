<script context="module">
	export const prerender = true;
</script>

<script>
	// import Counter from '$lib/Counter/index.svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section>
	<!-- This example requires Tailwind CSS v2.0+ -->
	<div class="px-4 py-5 sm:px-6">
	  <h3 class="text-lg leading-6 text-center font-medium text-gray-900">
		Svelte & Tailwind CSS
	  </h3>
	  <p class="mt-1 max-w-2xl text-sm text-center text-gray-500">
		Basic setup
	  </p>
	</div>
	
  
</section>

<style style lang="postcss">
	section {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 1;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
