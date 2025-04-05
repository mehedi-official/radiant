<script lang="ts">
	import { arrow_down_feather_icon, arrow_right_up, arrow_up, more } from './icons/Icons.svelte';
	import progress_img from '$lib/assets/progress_img.png';
</script>

<section class="min-h-76 rounded-2xl bg-neutral-200">
	<section class="flex items-center justify-between px-3.5 pt-3.5">
		<div class="flex items-center gap-1.5">
			<span class="bg-primary block h-4.5 w-4.5 rounded-md"></span>
			<h4 class=" text-secondary-200 text-sm/base font-semibold">Progress</h4>
		</div>

		<button
			class="flex aspect-square h-7 cursor-pointer items-center justify-center gap-2 rounded-full bg-white"
			>{@render more()}</button
		>
	</section>

	<section class="mt-5 grid grid-cols-[96px_1fr] gap-2 px-3.5">
		<div class="bg-secondary-300 aspect-square w-full overflow-hidden rounded-xl">
			<img src={progress_img} alt="A man wathcing his apple watch" />
		</div>
		<section class="flex flex-col justify-between">
			<div class="flex justify-end gap-1.5 pr-3">
				<p class=" text-xs/base text-secondary-200 font-medium">Running</p>
				<p class=" text-3xl/base text-secondary-200 font-medium">139</p>
			</div>
			<div class="text-[10px]/base text-secondary-100 flex flex-wrap gap-1.5 font-normal">
				<span class="flex h-4.5 w-fit items-center justify-center rounded-full bg-white px-2 py-2"
					>Running</span
				>
				<span class="flex h-4.5 w-fit items-center justify-center rounded-full bg-white px-2 py-2"
					>Sport</span
				>
				<span class="flex h-4.5 w-fit items-center justify-center rounded-full bg-white px-2 py-2"
					>Workout</span
				>
				<span class="flex h-4.5 w-fit items-center justify-center rounded-full bg-white px-2 py-2"
					>Checkout Daily</span
				>
			</div>
		</section>
	</section>

	<section class="flex items-center justify-between px-3.5 pt-5">
		<div class="flex items-center gap-1.5">
			<span class="bg-primary block h-4.5 w-4.5 rounded-md"></span>
			<h4 class=" text-secondary-200 text-sm/base font-semibold">Checkbox</h4>
		</div>

		<div class="flex items-center gap-1.5">
			<button
				class="flex aspect-square h-7 cursor-not-allowed items-center justify-center gap-2 rounded-full border border-gray-200 text-gray-200"
				>{@render arrow_down_feather_icon()}</button
			>
			<button
				class="border-secondary-200 flex aspect-square h-7 cursor-pointer items-center justify-center gap-2 rounded-full border"
				>{@render arrow_up()}</button
			>
		</div>
	</section>

	<section class="mt-5 px-3.5 pb-6">
		<div class="grid grid-cols-[96px_1fr] gap-3 border-b border-gray-300/50 py-1.5 pr-1.5 pl-1">
			<div class="flex items-center gap-2.5">
				<input
					type="checkbox"
					class=" form-checkbox text-secondary-200 h-4 w-4 appearance-none rounded-md border-none bg-white shadow-none outline-none focus:border-none focus:ring-neutral-200 focus:outline-none"
				/>
				<h4 class="text-base/base text-secondary-100 font-medium tracking-tight">0.5h45s</h4>
			</div>
			<div class="flex items-center justify-between">
				<p class=" text-xs/base text-secondary-100 font-medium">Workout</p>
				<span
					class="text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-medium"
					><span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>1/8</span
				>
			</div>
		</div>
		<div class="grid grid-cols-[96px_1fr] gap-3 border-b border-gray-300/50 py-1.5 pr-1.5 pl-1">
			<div class="flex items-center gap-2.5">
				<input
					type="checkbox"
					class=" form-checkbox text-secondary-200 h-4 w-4 appearance-none rounded-md border-none bg-white shadow-none outline-none focus:border-none focus:ring-neutral-200 focus:outline-none"
				/>
				<h4 class="text-base/base text-secondary-100 font-medium tracking-tight">Apple</h4>
			</div>
			<div class="flex items-center justify-between">
				<p class=" text-xs/base text-secondary-100 font-medium">Fruit Juice</p>
				<span
					class="text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-medium"
					><span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>1/2</span
				>
			</div>
		</div>
		<div class="grid grid-cols-[96px_1fr] gap-3 border-b border-gray-300/50 py-1.5 pr-1.5 pl-1">
			<div class="flex items-center gap-2.5">
				<input
					type="checkbox"
					checked
					class=" form-checkbox text-secondary-200 h-4 w-4 appearance-none rounded-md border-none bg-white shadow-none outline-none focus:border-none focus:ring-neutral-200 focus:outline-none"
				/>
				<h4 class="text-base/base text-secondary-200 font-medium tracking-tight">4.596km</h4>
			</div>
			<div class="flex items-center justify-between">
				<p class=" text-xs/base text-secondary-100 font-medium">Running</p>
				<span
					class="bg-primary text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-medium"
					><span class="h-2.5 w-2.5">{@render arrow_right_up()}</span>139</span
				>
			</div>
		</div>
		<div class="grid grid-cols-[96px_1fr] gap-3 py-1.5 pr-1.5 pl-1">
			<div class="flex items-center gap-2.5">
				<input
					type="checkbox"
					class=" form-checkbox text-secondary-200 h-4 w-4 appearance-none rounded-md border-none bg-white shadow-none outline-none focus:border-none focus:ring-neutral-200 focus:outline-none"
				/>
				<h4 class="text-base/base text-secondary-100 font-medium tracking-tight">3000ml</h4>
			</div>
			<div class="flex items-center justify-between">
				<p class=" text-xs/base text-secondary-100 font-medium">Water</p>
				<span
					class="text-xs/base text-secondary-200 inline-flex h-fit items-center justify-center gap-1 rounded-full py-1 pr-2.5 pl-2 font-medium"
					>More <span class="h-4 w-4">{@render arrow_right_up()}</span></span
				>
			</div>
		</div>
	</section>
</section>
