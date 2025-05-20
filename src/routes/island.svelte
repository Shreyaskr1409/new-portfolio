<script>
	import Leftbox from './leftbox.svelte';
	import Rightbox from './rightbox.svelte';
</script>

<div
	class="w-full max-w-[1050px] h-[640px] bg-[#d6bd91ad] rounded-3xl shadow-[0_0_25px_#000000c4]
    p-2 flex flex-row gap-2 items-center max-md:h-fit max-md:flex-col"
>
	<Leftbox></Leftbox>
	<span class="h-5/6 border-1 max-md:w-5/6"></span>
	<Rightbox></Rightbox>
</div>
