<script lang="ts">
	import Breath from './Breath.svelte';
	import Slider from './Slider.svelte';
	import Workout from './Workout.svelte';
</script>

<section class="mt-4 grid grid-cols-[1.68fr_1.54fr_1fr] gap-4 pb-10">
	<Slider />
	<Breath />
	<Workout />
</section>
