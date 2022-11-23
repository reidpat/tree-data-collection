<script>
    export let description;
    export let formula;

</script>

<div class="formula-container">
<p>{description}</p>
<div class="flex-class">
<code><pre>{formula}</pre></code>
<button on:click={() => navigator.clipboard.writeText(formula)}>Copy</button>
</div>
</div>

<style>
    .flex-class{
        display: flex;
        margin: auto;
        align-content: center;
        justify-content: center;
    }
    .formula-container{
        margin: 10px;
        font-size: large;
        text-align: center;
        border: 2px solid grey;
        border-radius: 5px;
        padding: 10px;
        background-color: rgb(255, 253, 243);
        width: 400px;
        }
    button {
        height: 30px;
        margin-left: 10px;
        align-self: center;

    }
</style>