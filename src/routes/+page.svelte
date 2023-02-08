<script>
	import Header from "./components/header.svelte";
	import Cards from "./components/cards.svelte";
	import Footer from "./components/footer.svelte";
	import Button from "./components/button.svelte";
</script>

<svelte:head><link rel="stylesheet" href="all.css"></svelte:head>

<body>
		<div class="content">
			<Header/>
			<div class="cards">
				<Cards />
			</div>
			<Button/>
			<div class="footer"><Footer/></div>
		</div>
</body>

<style>
	:root {
		--dark: #191919;
		--light: #ECDBBA;
		--shade: #2D4263;
		--shadow: #C84B31;
	}
	body {
		font-family: 'Trebuchet MS', sans-serif;
		background-color: var(--dark);
		text-align: center;        
		text-shadow: 1px 1px var(--shadow);
		margin: -10px;
		height: max-content;

		position: relative;
	}
	body::before {
		content: "";
		position: absolute;
		top: 0;
		left: 0;
		width: 100%;
		height: 100%;
		background-image: url(https://cdnb.artstation.com/p/assets/images/images/030/555/445/original/runny-run-homegiffy.gif?1600953104);
		background-repeat: no-repeat;
		background-size: cover;
		opacity: 0.3;
	}
	@media screen and (max-width: 1000px) {
		body::before {
			content: "";
			position: absolute;
			top: 0;
			left: 0;
			width: 100%;
			height: 100%;
			background-image: url(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2Foriginals%2F20%2F2d%2Fa0%2F202da09c9655941d4268d8a756f405fa.gif&f=1&nofb=1&ipt=f9a75eca1abcc62dfcc9d4158bf2336d98142caaba520c60f7b0292284f9bd0d&ipo=images);
			background-repeat: no-repeat;
			background-size: cover;
			opacity: 0.3;
		}
    }
	.cards {
		margin-top: 4em;
	}
	.footer {
		width: 100%;
	}
	.content {
		position: relative;
    }

</style>