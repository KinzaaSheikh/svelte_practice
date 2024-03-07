<script>
    let siren = '../siren.svg'
</script>

<header data-sveltekit-preload-data="false">
    <div class="logo">
        <!-- <img src={siren} alt="Logo"> -->
        <h2>Svelte Project</h2>
    </div>
    <div class="nav">
        <a href='/'>Home</a>
        <a href='/'>About</a>
        <a href='/'>Events</a>
        <a href='/'>Speaker</a>
        <a href='/'>Contact</a>
    </div>
</header>

<div class="hero">
    <h1>Welcome to SvelteKit</h1>
    <p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</div>

<style>
    :global(body) {
        height: 100vh;
        background-image: linear-gradient(rgba(15, 138, 125),rgba(10, 90, 81), #213253 );
    }

    header {
        background-color: rgba(15, 138, 125);
        display: flex;
    }
    h1 {
        color: aliceblue;
    }
    a{
        text-decoration: none;
        color: aliceblue;
    }
    .hero {
        position: relative;
        margin: auto
    }
</style>