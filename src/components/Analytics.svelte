<script>
	import { arrow_right_up, check, dna, minus, plus } from './icons/Icons.svelte';
</script>

<section class="flex flex-col justify-between rounded-2xl bg-neutral-100 px-3.5 pt-3.5 pb-4">
	<div class="flex justify-between gap-4">
		<section class="flex flex-col gap-4">
			<div class="flex items-center gap-1.5">
				<span class="bg-primary block h-4.5 w-4.5 rounded-md"></span>
				<h4 class=" text-secondary-200 text-sm/base font-semibold">Analytics</h4>
			</div>

			<div class="ml-6 flex items-end gap-6">
				<span class="text-secondary-200 text-sm/base font-medium">Tracker</span>

				<div class="flex gap-4">
					<p class=" text-3xl/base text-secondary-200 font-medium">
						9.45 <sup class=" text-sm/base">AM</sup>
					</p>
					<div
						class="bg-primary text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal"
					>
						<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>30min
					</div>
				</div>

				<div class="flex gap-4">
					<p class=" text-3xl/base text-secondary-200 font-medium">
						98.57 <sup class=" text-sm/base">F</sup>
					</p>
					<div
						class="bg-primary text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal"
					>
						<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>0.7%
					</div>
				</div>
			</div>
		</section>

		<div class="flex flex-col items-center gap-1">
			<button class="flex h-9 w-9 cursor-pointer items-center justify-center rounded-full bg-white"
				>{@render dna()}</button
			>

			<div class="flex flex-col">
				<button class=" border-b border-gray-200 py-2">{@render plus()}</button>
				<button class="py-2">{@render minus()}</button>
			</div>
		</div>
	</div>

	<section class="flex flex-col gap-10">
		<section class="flex items-end gap-11">
			<div
				class=" text-xs/base text-secondary-200 flex h-full flex-col justify-between gap-2 font-medium"
			>
				<p>5.2%</p>
				<p>3.8%</p>
				<p>0.0%</p>
			</div>

			<section class="flex w-full items-end justify-between gap-2">
				<div class="group relative">
					<div
						class="bg-secondary-200 h-10 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
					<span
						class="text-xs/base text-secondary-200 absolute -bottom-3 left-1/2 -translate-x-1/2 translate-y-full font-medium"
						>Jan</span
					>
				</div>

				<div class="group relative">
					<div
						class="bg-secondary-200 h-11 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-12 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-16 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-25 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div class="min-h-34 w-6 cursor-pointer rounded-lg bg-[#CEFF43]"></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 min-h-30 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
					<span
						class="text-xs/base text-secondary-200 absolute -bottom-3 left-1/2 -translate-x-1/2 translate-y-full font-medium"
						>Jul</span
					>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-24 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-14 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-19 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-10 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-13 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
					<span
						class="text-xs/base text-secondary-200 absolute -bottom-3 left-1/2 -translate-x-1/2 translate-y-full font-medium"
						>Dec</span
					>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-12 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-16 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
				<div class="group relative">
					<div
						class="bg-secondary-200 h-25 w-6 cursor-pointer rounded-xl group-hover:bg-[#CEFF43]"
					></div>
					<button
						class="text-secondary-200 text-sm/base absolute -top-2 left-1/2 z-10 hidden -translate-x-1/2 -translate-y-full cursor-pointer rounded-full bg-white px-2.5 py-2 transition-all duration-300 group-hover:block"
						>3.02%</button
					>
					<span
						class="absolute top-1 left-1/2 hidden h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white group-hover:block"
					></span>
				</div>
			</section>
		</section>
		<section class="flex gap-2">
			<button class="bg-primary text-sm/base cursor-pointer rounded-md px-2.5 py-2 text-[#2A3A00]"
				>Tracker</button
			>
			<button
				class="text-secondary-200 text-sm/base cursor-pointer rounded-md border border-gray-100 px-2.5 py-2 hover:bg-[#F5F5F5]"
				>Medical Analytics</button
			>
			<button
				class="text-secondary-200 text-sm/base cursor-pointer rounded-md border border-gray-100 px-2.5 py-2 hover:bg-[#F5F5F5]"
				>Fitness Metrics</button
			>
			<button
				class="text-secondary-200 text-sm/base cursor-pointer rounded-md border border-gray-100 px-2.5 py-2 hover:bg-[#F5F5F5]"
				>Patient Insights</button
			>
			<button
				class="text-secondary-200 text-sm/base cursor-pointer rounded-md border border-gray-100 px-2.5 py-2 hover:bg-[#F5F5F5]"
				>AI Healthcare</button
			>
		</section>
	</section>
</section>
