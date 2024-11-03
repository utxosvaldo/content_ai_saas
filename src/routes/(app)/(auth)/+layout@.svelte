<script>
	import { toast, Toaster } from 'svelte-sonner';

	let { children } = $props();
</script>

<Toaster theme='dark' />
{@render children?.()}
