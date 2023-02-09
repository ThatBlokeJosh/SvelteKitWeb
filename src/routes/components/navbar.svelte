<script>
</script>

<main>

    <ul>
        <a href="mailto:joshtomrem@protonmail.com"><li><i class="fa-solid fa-envelope fa-2xl"></i></li></a>
        <a href="https://twitter.com/JoshBloke"><li><i class="fa-brands fa-twitter fa-2xl"></i></li></a>
        <a href="https://discord.com/users/549936556593512449"><li><i class="fa-brands fa-discord fa-2xl"></i></li></a>
        <a href="https://codepen.io/thatblokejosh"><li><i class="fa-brands fa-codepen fa-2xl"></i></li></a>
        <a href="https://github.com/ThatBlokeJosh"><li><i class="fa-brands fa-github fa-2xl"></i></li></a>
    </ul>

</main>

<style>

    i {
        color: var(--light);
        margin: 0;
        padding: 0;
        display: flex;
        justify-content: center;
        align-items: center;
        width: 70px;
        height: 70px;
        border: var(--light) 5px solid;
        border-radius: 50%;
        transition: all 0.5s ease-in-out;
        
    }

    @keyframes spin {
        0% {
            transform: rotate(0deg);
        }
        100% {
            transform: rotate(360deg);
        }
    }

    a {
        text-decoration: none;
    }
    @media screen and (max-width: 1000px) {
        i {
            width: 50px;
            height: 50px;
        }
    }
    ul {
    display: flex;
    flex-direction: row;
    justify-content: center;
    list-style-type: none;
    margin: 0;
    margin-right: 30px;
    }
    i:hover {
        background-color: var(--light);
        color: var(--shade);
        border-color: var(--shade);
        animation: spin 1s linear;
    }

</style>