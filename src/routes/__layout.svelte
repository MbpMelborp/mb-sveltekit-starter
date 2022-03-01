<script>
</script>

<div class="home">
	<slot />
</div>

<style global lang="postcss">
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
	.home {
		@apply w-screen min-h-screen flex flex-col items-center justify-center;
	}
</style>
