<script>
	export let titolo;
	export let descrizione;
	export let bottone;
</script>

<div class="Card_festival">
	<p class="titolo">{titolo}</p>
	<p class="descrizione">{descrizione}</p>
	<div class="Card_bottone">
		<p class="bottone">{bottone}</p>
	</div>
</div>

<style>
	.Card_festival {
		background-color: #000;
		border-radius: 20px;
		width: fit-content;
		padding: 10px;
		color: #14ff00;
		font-family: sans-serif;
	}

	.titolo {
		font-size: 32 px;
	}

	.descrizione {
		font-size: 9px;
	}

	.Card_bottone {
		background-color: #14ff00;
		border-radius: 20px;
		padding: 10px;
	}

	.bottone {
		font-size: 12px;
		color: white;
	}
</style>
