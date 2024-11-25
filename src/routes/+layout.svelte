<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<div class="container max-w-screen-2xl p-2">
	{@render children()}
</div>
