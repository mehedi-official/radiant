<script lang="ts">
	import '../app.css';
	import '@fontsource-variable/dm-sans';

	let { children } = $props();
</script>

{@render children()}

<style>
	:global(body) {
		font-family: 'DM Sans Variable', sans-serif;
	}
</style>
