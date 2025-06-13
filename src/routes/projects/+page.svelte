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
			body="SimpliBlog is a blogging + networking site where you can
            post your experiences, works and advices for people to learn
            from and refer to. The blogs support markdown making it very easy
            to style and adopt."
			background="bg-[url(/images/simpliblog.png)]"
		></Project>
		<Project
			title="Chip-8 Emulator"
			repoURL="https://github.com/Shreyaskr1409/go-chip8-emu"
			secTitle="Releases"
			secURL="https://github.com/Shreyaskr1409/go-chip8-emu/releases"
			tools="Go, Ebitengine"
			body="Chip-8 is a software which was designed to work like a real
            computer, on a real computer. It had architecture of it own, which
            was simple in itself but it lays a foundation of how the emulation
            devices work."
			background="bg-[url(/images/chip-8.png)]"
		></Project>
		<Project
			title="Nintendo Entertainment System (NES) Emulator"
			repoURL="https://github.com/Shreyaskr1409/SmartClassroom/tree/main"
			secURL="https://github.com/Shreyaskr1409/SmartClassroom/tree/main"
			tools="C, Raylib"
			body="This is an emulation of NES, a gaming console made in 80s
            which allowed users to play games through cartridges. Emulators have
            been an awesome tools which preserve hardware from years ago in software
            form which can run over different devices."
			background="bg-[url(/images/nes.png)]"
		></Project>
		<Project
			title="RiskEye"
			repoURL="https://github.com/Shreyaskr1409/RiskEye-Service"
			secURL="https://documenter.getpostman.com/view/36354773/2sAXxY2TK1"
			tools="NodeJS, JavaScript, Python"
			body="RiskEye is a Payments Fraud Detection SaaS which leverages AI
            to detect anomalies, raise issues and get an admin dashboard for what
            happens with your data."
			background="bg-[url(/images/riskeye.jpg)]"
		></Project>
	</div>
</div>
