<script>
	let name = 'Sveltekit';
	let src = 'example';
	let string = 'Some <strong>string</strong> text.';
</script>

<h1>Welcome to {name}</h1>
<img {src} alt="Example Image" />
<p>{@html string}</p>

<style>
	h1 {
		color: red;
	}
</style>
