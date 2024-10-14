<script>
    export let headingTitle;
</script>

<header>
    <h1>{headingTitle}</h1>
    <nav>
        <a href="/">Home</a>
        <a href="/">About</a>
        <a href="/">Contact</a>
    </nav>
</header>

<style>
    nav a {
        padding-right: 1.5em;
        font-weight: bold;
    }
    nav {
        background-color: salmon;
        padding: 0.5em;
        border: 2px solid rgb(182, 81, 44);
    }
</style>