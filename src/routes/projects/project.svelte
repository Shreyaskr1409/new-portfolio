<script>
	import { goto } from '$app/navigation';

	export let title = '';
	export let repoURL = '';
	export let secTitle = 'Website';
	export let secURL = '';
	export let tools = '';
	export let body = '';
	export let background = 'bg-black';
</script>

<div
	class="w-full flex flex-row min-h-[300px] p-2 backdrop-blur-md bg-[#00000080]
            rounded-2xl border-black border-2 gap-2 max-md:flex-col"
>
	<div
		class="min-w-1/2 w-1/2 h-full {background} bg-cover bg-center bg-top self-stretch rounded-xl max-md:w-full max-md:h-[300px] max-[35rem]:h-[200px]"
	></div>
	<div class="text-[#ffe4c4] font-raleway flex flex-col gap-1 items-start grow">
		<h1 class="font-catchy text-4xl">{title}</h1>
		<div class="flex flex-row w-full gap-1">
			<button
				class="bg-black cursor-pointer px-2 rounded-sm grow"
				on:click={() => {
					window.open(repoURL, '_blank');
				}}>GitHub</button
			>
			<button
				class="bg-black cursor-pointer px-2 rounded-sm grow"
				on:click={() => {
					window.open(secURL, '_blank');
				}}>{secTitle}</button
			>
		</div>
		<h2 class="w-full border-y-black border-y-2">
			Tools: {tools}
		</h2>
		<p class="grow">
			{body}
		</p>
		<button
			class="bg-black cursor-pointer px-2 rounded-sm self-stretch"
			on:click={() => {
				window.open(repoURL, '_blank');
			}}>Show More...</button
		>
	</div>
</div>
