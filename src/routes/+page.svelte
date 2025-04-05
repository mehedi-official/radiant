<script lang="ts">
	import ContentContainer from '@components/ContentContainer.svelte';
	import Header from '@components/Header.svelte';
	import Navbar from '@components/Navbar.svelte';
	import Sidebar from '@components/Sidebar.svelte';
</script>

<section class="grid grid-cols-[1fr_15fr]">
	<Sidebar />

	<main class="px-8 pt-6">
		<Navbar />
		<Header />
		<ContentContainer />
	</main>
</section>
