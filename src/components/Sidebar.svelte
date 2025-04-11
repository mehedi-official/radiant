<script lang="ts">
	import { arrow_left_down, layer, logo, logo_icon, maximize } from './icons/Icons.svelte';
</script>

<aside
	class="sticky top-0 flex h-dvh max-w-21 flex-col items-center justify-between bg-neutral-100 pt-6 pb-4"
>
	<div class="grid justify-items-center gap-1.5">
		<div>{@render logo()}</div>
		<p class=" text-secondary-200 text-base/normal font-medium tracking-tight">AI-BL</p>
	</div>

	<section class="grid justify-items-center gap-2">
		<a
			href="/"
			class="text-secondary-100 hover:bg-primary hover:text-secondary-200 flex h-11 w-11 items-center justify-center rounded-full bg-neutral-200 text-xs/normal font-medium"
			>{@render logo_icon()}</a
		>
		<a
			href="/"
			class="text-secondary-100 hover:bg-primary hover:text-secondary-200 flex h-11 w-11 items-center justify-center rounded-full bg-neutral-200 text-xs/normal font-medium"
			>SpO2</a
		>
		<a
			href="/"
			class="text-secondary-100 hover:bg-primary hover:text-secondary-200 flex h-11 w-11 items-center justify-center rounded-full bg-neutral-200 text-xs/normal font-medium"
			>BMD</a
		>
		<a
			href="/"
			class="text-secondary-100 hover:bg-primary hover:text-secondary-200 flex h-11 w-11 items-center justify-center rounded-full bg-neutral-200 text-xs/normal font-medium"
			>Pulse</a
		>
		<a href="/" class="bg-primary flex h-11 w-11 items-center justify-center rounded-full"
			>{@render layer()}</a
		>
		<a
			href="/"
			class=" text-secondary-200 hover:bg-primary hover:text-secondary-200 flex items-center justify-center rounded-full bg-white px-4 py-2 text-xs/normal font-medium"
			>{new Date().getHours()}:{new Date().getMinutes()}</a
		>
	</section>

	<div class="grid gap-2">
		<button
			class="text-secondary-200 flex h-11 w-11 cursor-pointer items-center justify-center rounded-full bg-white"
			>{@render maximize()}</button
		>
		<button
			class="bg-secondary-200 flex h-11 w-11 cursor-pointer items-center justify-center rounded-full text-white"
			>{@render arrow_left_down()}</button
		>
	</div>
</aside>
