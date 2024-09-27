<script>
    export let year = 2024;
    export let pic;
    export let picname;

    let currentTime = new Date();
</script>

<div>
    <img src={pic} alt={picname}>
    <p>&copy; Web 1 {year}: the time is currently: {currentTime}</p>
</div>



<style>
    div {
        display: flex;
        flex-direction:column;
    }
    p {
        background-color: salmon;
        padding: 2em;
        font-weight: bold;
        font-size:x-small;
        border: 10px dotted bisque;
    }
</style>