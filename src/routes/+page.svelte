<script>
    import Footer from '$lib/Footer.svelte';
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<Footer year={2022}/>
<Footer year={2023}/>
<Footer year={1980}/>

<style>
    :global(*) {
        font-family: sans-serif;
    }
</style>