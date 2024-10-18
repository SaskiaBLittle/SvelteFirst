<script>
    export let where = "/";
    export let title = Empty;
    export let age = 0;
    export let info = Empty;
</script>

<div class="card" >
    <h2><b><a href={where}>{title}</a></b></h2>
    <p>{age}</p>
    <p>{info}</p>
</div>


<style>
    h2 {
        background-color:rgba(180, 73, 73, 0.89);
        padding: 0.7em;
    }
    p {
        padding-left: 0.7em;
    }
    .card {
        box-shadow: 0 4px 8px 0 rgba(0,0,0,0.2);
        transition: 0.3s;
        padding: 2px 16px;
        width: fit-content;
    }
    .card:hover {
        box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
    }
</style>