<script>
	import { goto } from '$app/navigation';
</script>

<nav
	class="w-full fixed flex justify-between items-center border-b-[#ffe4c4] border-b-2
    bg-[url('/images/gradient_navbar-min.png')] bg-cover text-[#ffe4c4] font-catchy
    shadow-md shadow-zinc-700 h-12 z-100"
>
	<!--navbar will be divided into two parts-->
	<div id="left part" class="flex items-center">
		<div id="lp_box" class="aspect-square m-1 w-8 bg-[#7fffd4]"></div>
		<button
			class="text-5xl text-[50px] hover:text-shadow-lg text-shadow-[#000000C0] duration-100 cursor-pointer"
			on:click={() => {
				goto('/');
			}}
		>
			Portfolio
		</button>
	</div>
	<div id="right part" class="flex gap-2 items-center">
		<button
			class="navigation text-lg text-[17px] bg-[#00000040] px-2 rounded-lg underline hover:scale-110 duration-100 cursor-pointer"
			on:click={() => {
				goto('/projects');
			}}
		>
			PROJECTS
		</button>
		<button
			class="navigation text-lg text-[17px] bg-[#00000040] px-2 rounded-lg underline hover:scale-110 duration-100 cursor-pointer"
			on:click={() => {
				window.open('/pdfs/resume.pdf', '_blank');
			}}
		>
			RESUME
		</button>
		<button
			class="navigation text-lg text-[17px] bg-[#00000040] px-2 rounded-lg underline hover:scale-110 duration-100 cursor-pointer"
		>
			CONTACT
		</button>
		<button
			class="navigation text-lg text-[17px] bg-[#00000040] px-2 rounded-lg underline hover:scale-110 duration-100 cursor-pointer"
		>
			ABOUT
		</button>
		<div id="rp_box" class="aspect-square m-1 w-8 bg-[#7fffd4]"></div>
	</div>
</nav>
