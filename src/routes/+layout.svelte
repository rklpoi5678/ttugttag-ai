<script lang="ts">
	import '../app.css';
	import Navigation from './Navigation.svelte';
	import Footer from './Footer.svelte';
	let { children } = $props();
</script>

<Navigation />
{@render children()}
<Footer />
