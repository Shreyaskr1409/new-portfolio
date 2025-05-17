<script lang="ts">
	import '../app.css';
	import Navbar from './navbar.svelte';

	let { children } = $props();
</script>

<!--Head will be loaded here-->
<svelte:head></svelte:head>

<Navbar></Navbar>

{@render children()}
