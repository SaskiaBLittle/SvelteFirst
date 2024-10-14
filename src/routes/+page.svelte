<script>
    import Header from '$lib/Header.svelte';
    import Footer from '$lib/Footer.svelte';
    import Image from '$lib/Image.svelte';
    import homepic from '$lib/demonslayer.jpg';
</script>

<Header headingTitle="Home Page" />
<!--<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>-->
<div class="imageContainor">
    <Image pic={homepic} picname={"cover"} />
</div>


<Footer year={2022} />
<!-- <Footer year={2023}/>
<Footer year={1980}/> -->

<style>
    :global(*) {
        font-family: sans-serif;
    }
    .imageContainor {
        display: flex;
        justify-content: center;
    }
</style>