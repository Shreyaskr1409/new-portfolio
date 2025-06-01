<script>
	import Project from './project.svelte';
</script>

<div
	class="w-full h-lvh bg-[url('/images/magicpattern-87PP9Zd7MNo-unsplash-min.jpg')] bg-cover
    flex flex-col justify-start items-center p-4 pt-18 max-md:h-auto"
>
	<div
		class="w-full rounded-2xl
        p-2 grid grid-cols-2 gap-2 max-2xl:grid-cols-1"
	>
		<Project
			title="SimpliBlog"
			repoURL="https://github.com/Shreyaskr1409/SimpliBlog"
			secURL="https://simpliblog.site/"
			tools="SvelteKit, JavaScript, NodeJS, MongoDB, Nginx"
			body="Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Optio quod nam, earum reprehenderit voluptas reiciendis nobis
            aliquam molestias atque! Corporis at eos sit natus optio unde,
            nesciunt id cum obcaecati."
			background="bg-[url(/images/simpliblog.png)]"
		></Project>
		<Project
			title="Chip-8 Emulator"
			repoURL="https://github.com/Shreyaskr1409/go-chip8-emu"
			secTitle="Releases"
			secURL="https://github.com/Shreyaskr1409/go-chip8-emu/releases"
			tools="Go, Ebitengine"
			body="Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Optio quod nam, earum reprehenderit voluptas reiciendis nobis
            aliquam molestias atque! Corporis at eos sit natus optio unde,
            nesciunt id cum obcaecati."
			background="bg-[url(/images/chip-8.png)]"
		></Project>
		<Project
			title="Nintendo Entertainment System (NES) Emulator"
			repoURL="https://github.com/Shreyaskr1409/SmartClassroom/tree/main"
			secURL="https://github.com/Shreyaskr1409/SmartClassroom/tree/main"
			tools="C, SDL2"
			body="Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Optio quod nam, earum reprehenderit voluptas reiciendis nobis
            aliquam molestias atque! Corporis at eos sit natus optio unde,
            nesciunt id cum obcaecati."
			background="bg-[url(/images/nes.png)]"
		></Project>
		<Project
			title="RiskEye"
			repoURL="https://github.com/Shreyaskr1409/RiskEye-Service"
			secURL="https://documenter.getpostman.com/view/36354773/2sAXxY2TK1"
			tools="NodeJS, JavaScript, Python"
			body="Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Optio quod nam, earum reprehenderit voluptas reiciendis nobis
            aliquam molestias atque! Corporis at eos sit natus optio unde,
            nesciunt id cum obcaecati."
			background="bg-[url(/images/riskeye.jpg)]"
		></Project>
		<Project
			title="Smart Classroom"
			repoURL="https://github.com/Shreyaskr1409/SmartClassroom"
			secURL="https://github.com/Shreyaskr1409/SmartClassroom"
			tools="Go, Python"
			body="Lorem ipsum dolor, sit amet consectetur adipisicing elit.
            Optio quod nam, earum reprehenderit voluptas reiciendis nobis
            aliquam molestias atque! Corporis at eos sit natus optio unde,
            nesciunt id cum obcaecati."
		></Project>
	</div>
</div>
