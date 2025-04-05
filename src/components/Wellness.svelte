<script>
	import { arrow_right_up } from './icons/Icons.svelte';
</script>

<section class="flex flex-col justify-between rounded-2xl bg-neutral-100">
	<div>
		<section class="flex items-center justify-between px-3.5 pt-3.5">
			<div class="flex items-center gap-1.5">
				<span class="bg-primary block h-4.5 w-4.5 rounded-md"></span>
				<h4 class=" text-secondary-200 text-sm/base font-semibold">Wellness</h4>
			</div>

			<button
				class="text-xs/base text-secondary-200 flex h-8 items-center gap-2 rounded-full bg-white py-1.5 pr-3 pl-1.5 font-semibold"
			>
				<span class=" bg-secondary-200 block aspect-square h-full rounded-full"></span>
				News
			</button>
		</section>

		<section class="mt-5 grid gap-14 p-3.5">
			<div class="flex justify-between">
				<div class="grid gap-1">
					<p class=" text-secondary-200 text-3xl/base font-medium tracking-tight">19,365.29</p>
					<p class=" text-xs/base text-secondary-200 font-semibold">KCAL Totally</p>
				</div>
				<div
					class="bg-primary text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal"
				>
					<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
				</div>
			</div>

			<div>
				<p class=" text-xs/base text-secondary-200 max-w-44 font-medium uppercase">
					Perfect Wellness metrics based on Blockchain
				</p>
				<div></div>
			</div>
		</section>
	</div>

	<section class="mt-2 grid grid-cols-2 border-t border-gray-300/50">
		<section class="flex flex-col justify-between gap-7 border-r border-gray-300/50 px-3 py-2">
			<div class="grid gap-2">
				<p class="text-secondary-200 text-3xl/base font-medium tracking-tight">265</p>
				<p class="text-xs/base text-secondary-200 font-semibold">KCAL</p>
			</div>
			<p class="text-xs/base text-secondary-200 max-w-14 font-semibold">Calories Burned</p>
		</section>
		<section class="flex flex-col justify-between py-2 pr-2 pl-3">
			<div class="flex justify-between">
				<p class="text-secondary-200 text-3xl/base font-medium tracking-tight">8</p>
				<div class="flex flex-col items-end gap-1">
					<div
						class="text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full bg-neutral-200 py-1 pr-2.5 pl-2 font-normal"
					>
						<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>24%
					</div>
					<p class="text-xs/base text-secondary-200 pr-2 font-semibold">2d</p>
				</div>
			</div>
			<p class="text-xs/base text-secondary-200 font-semibold">Workouts Completed</p>
		</section>
	</section>
</section>
