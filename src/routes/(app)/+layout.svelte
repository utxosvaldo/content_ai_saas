<script>
	import Footer from '$lib/layout/Footer.svelte';
	import Header from '$lib/layout/Header.svelte';

	let { children } = $props();
</script>


<div class="min-h-screen bg-background font-sans antialiased">
	<Header />
	<div class="mx-auto flex-1 overflow-hidden">
		{@render children?.()}
	</div>
	<Footer />
</div>
