<script lang="ts">
	import { arrow_down, arrow_right, arrow_right_down, calendar, clock } from './icons/Icons.svelte';
</script>

<header class="mt-9 flex items-end justify-between">
	<section class="flex items-end gap-4">
		<div class="grid">
			<h3 class=" text-4xl/base text-secondary-300 font-normal tracking-tight">Health Records</h3>
			<h2 class=" text-[44px]/base text-secondary-200 font-medium tracking-tight">Dashboard</h2>
		</div>

		<div class="flex items-end gap-2">
			<div class="bg-primary grid h-16 w-16 -translate-y-1.5 place-content-center rounded-full">
				<svg
					width="27"
					height="26"
					viewBox="0 0 27 26"
					fill="none"
					xmlns="http://www.w3.org/2000/svg"
				>
					<rect
						x="7"
						y="1.02637"
						width="3"
						height="26"
						transform="rotate(-20 7 1.02637)"
						fill="#2D2F33"
					/>
					<rect
						x="20.2998"
						y="2.24316"
						width="3"
						height="26"
						transform="rotate(39.74 20.2998 2.24316)"
						fill="#2D2F33"
					/>
					<rect
						y="11.9414"
						width="3"
						height="26"
						transform="rotate(-78.6915 0 11.9414)"
						fill="#2D2F33"
					/>
				</svg>
			</div>
			<div class="bg-secondary-200 grid h-8 w-8 place-content-center rounded-full">
				{@render arrow_right_down()}
			</div>
		</div>
	</section>
	<section class="flex items-center gap-2">
		<button
			class="flex h-12 w-fit cursor-pointer items-center gap-3 rounded-full bg-neutral-200 py-1.5 pr-3 pl-1.5 text-white"
		>
			<div class="grid aspect-square h-full place-content-center rounded-full bg-white">
				{@render calendar()}
			</div>
			<p class=" text-secondary-200">Sep 02 - Sep 09</p>
			<span class="grid h-6 w-6 place-content-center rounded-full bg-white"
				>{@render arrow_down()}</span
			>
		</button>

		<button
			class="flex h-12 w-fit cursor-pointer items-center gap-3 rounded-full bg-neutral-200 py-1.5 pr-3 pl-1.5 text-white"
		>
			<div class="grid aspect-square h-full place-content-center rounded-full bg-white">
				{@render clock()}
			</div>
			<p class=" text-secondary-200">24h</p>
			<span class="grid h-6 w-6 place-content-center rounded-full bg-white"
				>{@render arrow_down()}</span
			>
		</button>

		<button
			class="bg-secondary-200 flex h-12 w-fit cursor-pointer items-center gap-3 rounded-full py-2.5 pr-2.5 pl-5 text-white"
		>
			<p>Weekly</p>
			<span class="grid aspect-square h-full place-content-center rounded-full bg-white"
				>{@render arrow_right()}</span
			>
		</button>
	</section>
</header>
