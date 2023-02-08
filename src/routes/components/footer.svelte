<script>
    import Navbar from "./navbar.svelte";
</script>

<main>

    
    <div class="footer">
        <nav><Navbar/></nav>
    </div>
</main>

<style>
    main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}
    nav {
		box-sizing: border-box;
        padding: 5em;
        display: flex;
        justify-content: bottom center;
        align-items: bottom center;
        flex-direction: column;
        height: 100%;
        width: 100%;

	}
</style>