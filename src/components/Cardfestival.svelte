<script>
	export let titolo;
	export let descrizione;
	export let bottone;
	export let link;
</script>

<div class="Card_festival">
	<p class="titolo">{titolo}</p>
	<p class="descrizione">{descrizione}</p>
	<a class="Card_bottone" href={link}>
		<p class="bottone">{bottone}</p>
	</a>
</div>

<style>
	.Card_festival {
		background-color: #000;
		border-radius: 20px;
		width: fit-content;
		padding: 10px;
		color: #14ff00;
		font-family: sans-serif;

		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	.titolo {
		font-size: 32 px;
		text-align: center;
	}

	.descrizione {
		font-size: 9px;
		text-align: center;
	}

	.Card_bottone {
		background-color: #14ff00;
		border-radius: 20px;
		padding: 10px;
		margin-top: 10px;
	}

	.bottone {
		font-size: 12px;
		color: white;
		text-align: center;
	}
</style>
