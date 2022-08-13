<script context="module">
	let name = '';
	/** @type {import('./__types/[name]').Load} */
	export async function load({ params }) {
		name = params.name;
	}
</script>

<svelte:head>
	<title>Greet</title>
</svelte:head>

<h1>Hello {name}</h1>

<a href="/">Home</a>
