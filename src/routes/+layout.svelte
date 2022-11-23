
<script>
    import "../app.css";
</script>

<div>
<div class="image"></div>
<slot />
</div>

<style>
    div.image{
        width: 100%;
        height:100%;
        position: fixed;
        top:0px;
        left:0px;
        background: url("/forest.jpg") no-repeat center center fixed; 
        -webkit-background-size: cover;
        -moz-background-size: cover;
        -o-background-size: cover;
        background-size: cover;
        z-index: -10;
    }
</style>