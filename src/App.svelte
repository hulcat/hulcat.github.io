<script>
	export let name;
	const network = "juno";
	const contractAddress = "juno1pshrvuw5ng2q4nwcsuceypjkp48d95gmcgjdxlus2ytm4k5kvz2s7t9ldx";
	function addKeplrExtension() {
		window.keplr.suggestToken("juno", "juno1pshrvuw5ng2q4nwcsuceypjkp48d95gmcgjdxlus2ytm4k5kvz2s7t9ldx");
	}
</script>

<main>
	<h1>Hell<img src="./favicon.png">   {name}!</h1>
	<p><a href="https://github.com/hulcat/hulcat.github.io/blob/main/document/DISTRIBUTION.md" target="_blank">Distribution</a></p>
	<p><a href="https://github.com/hulcat/hulcat.github.io/blob/main/document/BOUNTIES.md" target="_blank">Bounties</a></p>
	<p><a href="#" on:click={addKeplrExtension}>Add keplr extension</a></p>
</main>

<style>
	img {
		margin-left: -8px;
		margin-right: 10px;
		width: 50px;
	}

	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: auto;
		height: 90vh;
    	display: flex;
    	justify-content: center;
    	align-items: center;
		flex-direction: column;
	}

	a {
		text-decoration: none;
	}

	h1 {
		color: #5BC62E;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 90;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>
