<script>
    import Header from '$lib/Header.svelte';
    import Card from '$lib/Card.svelte';
    import Footer from '$lib/Footer.svelte';
    import Image from '$lib/Image.svelte';
    import homepic from '$lib/demonslayer.jpg';
</script>

<Header headingTitle="Home Page" />
<!--<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>-->
<div class="imageContainor">
    <Image pic={homepic} picname={"cover"} />
</div>

<Card where="/about" title="Tanjiro Kamado" age=15 info="A Demon Slayer" />

<Footer year={2022} />


<style>
    :global(*) {
        font-family: sans-serif;
    }
    .imageContainor {
        display: flex;
        justify-content: center;
    }
</style>