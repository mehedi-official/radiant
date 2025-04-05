<script lang="ts">
	import Progress from './Progress.svelte';
	import Wellness from './Wellness.svelte';
</script>

<section class="grid grid-cols-[1fr_2.6fr_1.12fr] gap-4">
	<Wellness />

	<section class=" min-h-76 bg-neutral-100">
		<section>
			<div>
				<h4>Wellness</h4>
			</div>
		</section>
	</section>

	<Progress />
</section>
