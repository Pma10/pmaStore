<script>
	import {Router,Link,Route} from 'svelte-routing';
	import Header from './Header.svelte';
	import MainPage from './+page.svelte';
	import AboutPage from './about/+page.svelte';
	import HelpPage from './help/+page.svelte';
	import Footer from './Footer.svelte';
	export let url = 'localhost';
</script>

<Header />

<Router url="{url}">
	<Route path="about" component="{AboutPage}" />
	<Route path="help" component="{HelpPage}" />
	<Route path="/" component="{MainPage}" />
</Router>
<slot />
<footer>
	<Footer />
</footer>

<style>
	:global(body) {
		background-color: #181818;
	}
</style>
