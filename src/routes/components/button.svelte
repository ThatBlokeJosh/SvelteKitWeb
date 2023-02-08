<script>
    let show = false;
    function handleClick() {
        if (show == true) {
            show = false;
        } else {
            show = true;
        }
    }
</script>

{#if show === false}
<button class="showmore btn button" on:click={handleClick}>Show more!</button>
{/if}

{#if show === true}
    <div class="section">
        <h1><b>Hello, I'm Josh!</b></h1>
        <p>I'm a 16 year-old Czech programmer. Most of my programming was done in Python where I simple made games and applications in Pygame.
        Recently I became interested in web development and I'm currently learning Svelte, HTML, CSS and JS. I'm also learning C#.
        I'm fluent in Czech and English. I'm also a beginner Linux user. I like playing video games, cycling, reading and watching films.
        </p>
    </div>
    <button class="showmore btn button" on:click={handleClick} style="margin: 20px;">Show less!</button>
{/if}


<style>
    button {
        margin-top: 1%;
        width: 20%;
        padding: 10px 20px;
        background: var(--shade);
        outline: none;
        border: none;
        border-radius: 17px;
        font-weight: 700;
        transition: all 0.2s ease-in-out;
        cursor: pointer;
    }

    .button {
        text-decoration: none;
        color: var(--light);
        font-size: 100%;
        transition: all 0.2s ease-in-out;
    }

    .btn:hover {
        transform: scale(1.1);
        transition: all 0.2s ease-in-out;
    }
    .section {
        width: 90%;
        height: fit-content;
        margin: 0 auto;
        background-color: var(--shade);
        border-radius: 15px;
        border: var(--light) 10px solid;
        margin-top: 25px;
        color: var(--light);
    }
    h1 {
        font-size: 3em;
        font-weight: 1000;
        width: 100%;
    }
    p {
        font-size: 1.5em;
        font-weight: 500;
        padding: 0 5% 0 5%;
    }
    @media screen and (max-width: 1000px) {
        button {
            width: 50%;
        }
        h1 {
            font-size: 2em;
        }
        p {
            font-size: 1.2em;
        }
    }

</style>