<script>
	import SkipToContentButton from '../lib/SkipToContentButton.svelte'
	export let name;
</script>

<SkipToContentButton />

<nav>
	<ul>
		<li><a href="#link1">link1</a></li>
		<li><a href="#link2">link2</a></li>
		<li><a href="#link3">link3</a></li>
		<li><a href="#link4">link4</a></li>
		<li><a href="#link5">link5</a></li>
	</ul>
</nav>

<main id="content">
	<h1>Hello {name}!</h1>
	<a href="#hero-link">Learn more</a>
</main>


<style>
	ul {
		display: flex;
	}

	li {
		list-style-type: none;
	}

	li+li {
		margin-left: 24px;
	}

	h1 {
		color: purple;
	}

</style>
