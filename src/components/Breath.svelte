<script>
	import { arrow_right_up, fingerprint } from './icons/Icons.svelte';
</script>

<section class="grid grid-rows-2 gap-4">
	<section class="rounded-2xl bg-neutral-100 py-5 pr-5 pl-6">
		<div class="flex justify-between">
			<h2 class="text-secondary-200 max-w-34 text-xl/tight font-semibold uppercase">
				Take a breath now
			</h2>
			<p class=" text-secondary-100 max-w-32 text-right text-xs/snug">
				<span class=" text-secondary-200 font-semibold">Wait 2 sec,</span> and then take a deep breath!
			</p>
		</div>

		<div
			class="text-xs/base text-secondary-200 mt-3 flex items-center justify-between gap-4 rounded-full bg-white px-2 py-2 font-medium"
		>
			<div class="flex items-center gap-4">
				<span class="rounded-full bg-neutral-200 px-4 py-3">35, m2</span>
				<p>Breath level is normal now, 12</p>
			</div>
			<button class=" flex h-8 w-8 items-center justify-center rounded-full bg-neutral-200 p-2"
				>{@render fingerprint()}</button
			>
		</div>
	</section>

	<section class="flex items-end gap-3">
		<section
			class="bg-primary flex w-fit min-w-40 flex-col justify-between self-stretch rounded-2xl px-3 py-2.5"
		>
			<div class="flex flex-col gap-2">
				<div
					class="text-xs/base text-secondary-200 inline-flex h-fit w-fit items-center justify-center gap-1 rounded-full bg-white py-1 pr-2.5 pl-2 font-normal"
				>
					<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>0.6%
				</div>

				<div class="flex items-center gap-0.5">
					<div class="w-fit rounded-full p-1">
						<span class="block h-2.5 w-2.5 rounded-full bg-[#83984D]"></span>
					</div>
					<div class="w-fit rounded-full border border-[#29370E] p-1">
						<span class="block h-2.5 w-2.5 rounded-full bg-[#2D2F33]"></span>
					</div>
					<div class=" w-fit rounded-full p-1">
						<span class="block h-2.5 w-2.5 rounded-full bg-[#83984D]"></span>
					</div>
					<div class=" w-fit rounded-full p-1">
						<span class="block h-2.5 w-2.5 rounded-full bg-[#83984D]"></span>
					</div>
				</div>
			</div>

			<div class="flex flex-col gap-1.5">
				<p class=" text-xs/base text-[#2A3609]">db</p>
				<p class=" text-4xl/base font-medium text-[#2D2F32]">10.57</p>
			</div>
		</section>

		<section class="flex w-full items-end gap-4">
			<p class="text-secondary-100 max-w-14 text-xs/snug uppercase">Checkup. AI Based Model</p>

			<div class="flex w-full items-end justify-between gap-1.5">
				<div class="flex flex-col items-center gap-1.5">
					<div class="group relative cursor-pointer">
						<div class=" h-10 w-1 bg-neutral-200"></div>
						<span
							class="absolute top-0 left-1/2 block h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white bg-[#CEFF43]"
						></span>
						<div
							class="bg-primary text-xs/base text-secondary-200 absolute -top-3 left-1/2 hidden h-fit -translate-x-1/2 -translate-y-full items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal group-hover:inline-flex hover:inline-flex"
						>
							<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
						</div>
					</div>
					<span
						class="text-xs/base text-secondary-200 flex rounded-sm bg-neutral-200 px-1 py-1 font-medium"
						>S</span
					>
				</div>
				<div class="flex flex-col items-center gap-1.5">
					<div class="group relative cursor-pointer">
						<div class=" h-13 w-1 bg-neutral-200"></div>
						<span
							class="absolute top-0 left-1/2 block h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white bg-[#CEFF43]"
						></span>
						<div
							class="bg-primary text-xs/base text-secondary-200 absolute -top-3 left-1/2 hidden h-fit -translate-x-1/2 -translate-y-full items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal group-hover:inline-flex hover:inline-flex"
						>
							<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
						</div>
					</div>
					<span
						class=" text-xs/base text-secondary-200 flex rounded-sm bg-neutral-200 px-1 py-1 font-medium"
						>M</span
					>
				</div>
				<div class="flex flex-col items-center gap-1.5">
					<div class="group relative cursor-pointer">
						<div class=" h-16 w-1 bg-neutral-200"></div>
						<span
							class="absolute top-0 left-1/2 block h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white bg-[#CEFF43]"
						></span>
						<div
							class="bg-primary text-xs/base text-secondary-200 absolute -top-3 left-1/2 hidden h-fit -translate-x-1/2 -translate-y-full items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal group-hover:inline-flex hover:inline-flex"
						>
							<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
						</div>
					</div>
					<span
						class=" text-xs/base text-secondary-200 flex rounded-sm bg-neutral-200 px-1 py-1 font-medium"
						>T</span
					>
				</div>
				<div class="flex flex-col items-center gap-1.5">
					<div class="group relative cursor-pointer">
						<div class=" h-20 w-1 bg-neutral-200"></div>
						<span
							class="absolute top-0 left-1/2 block h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white bg-[#CEFF43]"
						></span>
						<div
							class="bg-primary text-xs/base text-secondary-200 absolute -top-3 left-1/2 inline-flex h-fit -translate-x-1/2 -translate-y-full items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal hover:inline-flex"
						>
							<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
						</div>
					</div>
					<span
						class=" text-xs/base text-secondary-200 flex rounded-sm bg-neutral-200 px-1 py-1 font-medium"
						>W</span
					>
				</div>
				<div class="flex flex-col items-center gap-1.5">
					<div class="group relative cursor-pointer">
						<div class=" h-17.5 w-1 bg-neutral-200"></div>
						<span
							class="absolute top-0 left-1/2 block h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white bg-[#CEFF43]"
						></span>
						<div
							class="bg-primary text-xs/base text-secondary-200 absolute -top-3 left-1/2 hidden h-fit -translate-x-1/2 -translate-y-full items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal group-hover:inline-flex hover:inline-flex"
						>
							<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
						</div>
					</div>
					<span
						class=" text-xs/base text-secondary-200 flex rounded-sm bg-neutral-200 px-1 py-1 font-medium"
						>T</span
					>
				</div>
				<div class="flex flex-col items-center gap-1.5">
					<div class="group relative cursor-pointer">
						<div class=" h-12 w-1 bg-neutral-200"></div>
						<span
							class="absolute top-0 left-1/2 block h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white bg-[#CEFF43]"
						></span>
						<div
							class="bg-primary text-xs/base text-secondary-200 absolute -top-3 left-1/2 hidden h-fit -translate-x-1/2 -translate-y-full items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal group-hover:inline-flex hover:inline-flex"
						>
							<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
						</div>
					</div>
					<span
						class=" text-xs/base text-secondary-200 flex rounded-sm bg-neutral-200 px-1 py-1 font-medium"
						>F</span
					>
				</div>
				<div class="flex flex-col items-center gap-1.5">
					<div class="group relative cursor-pointer">
						<div class=" h-14 w-1 bg-neutral-200"></div>
						<span
							class="absolute top-0 left-1/2 block h-4 w-4 -translate-x-1/2 rounded-full border-3 border-white bg-[#CEFF43]"
						></span>
						<div
							class="bg-primary text-xs/base text-secondary-200 absolute -top-3 left-1/2 hidden h-fit -translate-x-1/2 -translate-y-full items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-normal group-hover:inline-flex hover:inline-flex"
						>
							<span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>16%
						</div>
					</div>
					<span
						class=" text-xs/base text-secondary-200 flex rounded-sm bg-neutral-200 px-1 py-1 font-medium"
						>S</span
					>
				</div>
			</div>
		</section>
	</section>
</section>
