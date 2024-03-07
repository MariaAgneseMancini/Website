<script lang="ts">
	import Cardfestival from '$components/Cardfestival.svelte';

	let Cards = [
		{
			titolo: 'TICKETS',
			descrizione: 'Choose the best ticket based on your needs',
			bottone: 'Get them'
		},
		{
			titolo: 'HOTEL',
			descrizione: 'Choose the best hotel',
			bottone: 'Book now'
		},
		{
			titolo: 'TRANSPORT',
			descrizione: 'Discover all the possibilities to reach us',
			bottone: 'Come now'
		},
		{
			titolo: 'ACTIVITIES',
			descrizione: 'Make your experience even more enjoyable',
			bottone: 'Enjoy'
		}
	];
</script>

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@3.4.1/src/css/preflight.css" />
</svelte:head>

{#each Cards as Card}
	<Cardfestival titolo={Card.titolo} descrizione={Card.descrizione} bottone={Card.bottone} />
{/each}
