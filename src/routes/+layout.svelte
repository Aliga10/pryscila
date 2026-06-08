<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';
	import 	* as NavigationMenu from "$lib/components/ui/navigation-menu/index.js";
	let { children } = $props();
	import Header from '$lib/components/header/header.svelte';
	import Footer from '$lib/components/footer/footer.svelte';
	import { ModeWatcher } from "mode-watcher";
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>
<ModeWatcher />
<Header />
{@render children()}
<Footer />

