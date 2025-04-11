<script>
	import { arrow_right_up } from './icons/Icons.svelte';
	import workout_model from '$lib/assets/workout_model.png';
</script>

<section class="grid grid-cols-2 grid-rows-2 gap-4">
	<section class="flex flex-col justify-between pb-4">
		<div class="flex items-center gap-1.5">
			<span class="bg-primary block h-4.5 w-4.5 rounded-md"></span>
			<h4 class=" text-secondary-200 text-sm/base font-semibold">Workout</h4>
		</div>

		<div><img src={workout_model} alt="workout" /></div>
	</section>

	<section class="flex flex-col justify-end gap-4 pb-4">
		<div class="flex justify-between">
			<p class=" text-xs/base font-medium tracking-tight">Time Tracking</p>
			<div
				class="bg-primary text-[10px]/base text-secondary-200 inline-flex h-fit items-center justify-center gap-0.5 rounded-full py-1 pr-2 pl-1.5 font-normal"
			>
				<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
			</div>
		</div>

		<div class="flex items-end justify-between">
			<p class="text-xs/base text-secondary-200 font-medium">
				<span class=" text-5xl/[24px] font-medium">139</span>/160h
			</p>
			<p class="text-xs/base text-secondary-200 font-medium">7d</p>
		</div>
	</section>

	<section class="flex flex-col justify-between rounded-2xl bg-neutral-100 p-3">
		<div class="flex flex-col gap-2">
			<p class=" text-xs/base text-secondary-100">Oxygen</p>
			<h2 class="text-4xl/base text-secondary-200 font-medium">
				97.5<span class=" text-sm/base">%</span>
			</h2>
		</div>
		<p class="text-xs/base text-secondary-100">+ 0.2% from last week</p>
	</section>
	<section class="flex flex-col justify-between rounded-2xl bg-neutral-200 p-3">
		<div class="flex flex-col gap-2">
			<p class=" text-xs/base text-secondary-100">
				{new Date().getHours()}:{new Date().getMinutes()}
			</p>
			<h2 class="text-4xl/base text-secondary-200 font-medium">
				89<span class=" text-sm/base">bpm</span>
			</h2>
		</div>
		<p class="text-xs/base text-secondary-100">+ 7% from last week</p>
	</section>
</section>
