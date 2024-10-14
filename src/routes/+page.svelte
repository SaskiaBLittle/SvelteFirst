<script>
    import Header from '$lib/Header.svelte';
    import Footer from '$lib/Footer.svelte';
    import catpic from '$lib/cat.jpg';
</script>

<Header />
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Footer year={2022} pic={catpic} picname={"cat"} />
<!-- <Footer year={2023}/>
<Footer year={1980}/> -->

<style>
    :global(*) {
        font-family: sans-serif;
    }
</style>