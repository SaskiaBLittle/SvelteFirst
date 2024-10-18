<script>
    export let headingTitle;
</script>

<header>
    <nav>
        <a href="/">Home</a>
        <a href="/">Characters^</a>
        <a href="/">Seasons and Movie^</a>
        <a href="/">Quiz</a>
        <a class="side" href="/about">About</a>
        <a class="side" href="/contact">Contact</a>
    </nav>
    <h1>{headingTitle}</h1>
</header>

<style>
    nav a {
        float: left;
        color: #f2f2f2;
        text-align: center;
        padding: 3px 10px;
        text-decoration: none;
        font-weight: bold;
    }
    nav a:hover {
        background-color: #ddd;
        color: black;
    }
    nav {
        background-color: rgb(219, 69, 52);
        padding: 2em;
        border: 2px solid rgb(134, 57, 29);
    }
    .side {

    }
</style>