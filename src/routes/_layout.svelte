<script>
	import Nav from '../components/commom/Nav.svelte';
	export let segment;
</script>

<Nav {segment}/>
<main>
	<slot></slot>
</main>