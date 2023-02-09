<script>
</script>

<main>
	<div class="header">
		<div class="title">
			<h1>Welcome!</h1>
		</div>
	</div>
</main>
<style>
    main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

	h1 {
		color: var(--light);
		font-size: 4em;
		font-weight: 1000;
		width: 100%;
		text-shadow: 5px 5px var(--shadow);

	}

	@media screen and (max-width: 1000px) {
		h1 {
			font-size: 2em;
		}
	}

	@media screen and (min-height: 1200px) {
		h1 {
			font-size: 6em;
		}
	}
	.title {
		width: 50%;
		display: grid;
		grid-template-rows: 1fr;
		color: var(--light);
		margin: 0 auto;
		box-sizing: border-box;
	}

</style>