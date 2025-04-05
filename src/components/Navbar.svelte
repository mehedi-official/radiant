<script lang="ts">
	import {
		check,
		coffee,
		compass,
		heart,
		menu,
		notification,
		refresh,
		star
	} from './icons/Icons.svelte';
	import avatar from '$lib/assets/avatar.png';
</script>

<nav class="flex items-center justify-between">
	<section class="flex items-center gap-4">
		<div class="flex gap-1">
			<button
				class="flex h-12 w-12 cursor-pointer items-center justify-center rounded-full border-[1.5px] border-gray-100 hover:bg-gray-50"
				>{@render compass()}</button
			>
			<button
				class="flex h-12 w-12 cursor-pointer items-center justify-center rounded-full border-[1.5px] border-gray-100 hover:bg-gray-50"
				>{@render refresh()}</button
			>
			<button
				class="flex h-12 w-12 cursor-pointer items-center justify-center rounded-full border-[1.5px] border-gray-100 hover:bg-gray-50"
				>{@render check()}</button
			>
		</div>

		<div
			class="flex h-12 w-fit items-center gap-6 rounded-full border-[1.5px] border-gray-100 py-1.5 pr-4 pl-1.5"
		>
			<div class="flex items-center gap-2.5">
				<div class="aspect-square h-full overflow-hidden rounded-full">
					<img src={avatar} alt="user avatar" class="h-full w-full" />
				</div>
				<div class="flex flex-col gap-1">
					<h4 class=" text-sm/base text-secondary-200 font-medium tracking-tight">
						Celeste T. Koch
					</h4>
					<p class=" text-xs/base text-secondary-100 font-normal">@t.kockceles</p>
				</div>
			</div>
			<div class="flex items-center gap-5">
				<span>{@render heart()}</span>
				<span>{@render coffee()}</span>
				<span>{@render star()}</span>
			</div>
		</div>
	</section>
	<section class="flex items-center gap-2">
		<div
			class="flex h-12 w-fit items-center gap-2 rounded-full border-[1.5px] border-gray-100 py-1.5 pr-4 pl-1.5"
		>
			<div class=" grid aspect-square h-full place-content-center rounded-full bg-neutral-200">
				{@render notification()}
			</div>
			<p class=" text-base/base text-secondary-200 font-medium tracking-tight">
				{new Date().toLocaleDateString('en-US', {
					weekday: 'short',
					day: 'numeric',
					month: 'short'
				})}
			</p>
			<span
				class=" text-[10px]/base bg-secondary-200 grid h-4 place-content-center rounded-full px-2 font-normal text-white"
				>5</span
			>
		</div>
		<button
			class="grid aspect-square h-12 cursor-pointer place-content-center rounded-full border-[1.5px] border-gray-100 hover:bg-gray-50"
			>{@render menu()}</button
		>
	</section>
</nav>
