<script>
	import Header from './Header.svelte';
	import Page from './+page.svelte';
	import Footer from './Footer.svelte';
</script>

<div class="app">
	<Header/>

	<main>
		<Page />
	</main>

	<footer>
		<Footer />
	</footer>
</div>

<style>
	:global(body){
		background-color: #181818;
	}

</style>
