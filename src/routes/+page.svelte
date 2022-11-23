<script>
	import Formula from "../components/Formula.svelte";

    
</script>
<div>
<h1>Helpful Excel Formulas</h1>
<Formula description="Height Trig Calculation" formula="=TAN(RADIANS(D2))"/>
<Formula description="Total Cedar" formula="=COUNT(B:B)"/>
<Formula description="Total Hemlock" formula="=COUNT(C:C)"/>
<Formula description="Average Cedar Height" formula="=SUMIFS(E:E,B:B, 1)/COUNT(B:B)"/>
<Formula description="Average Hemlock Height" formula="=SUMIFS(E:E,C:C, 1)/COUNT(C:C)"/>
<Formula description="Average Heading" formula="=SUM(E:E)/COUNT(E:E)"/>
</div>

<style>
    div{
        padding-top: 40px;
        height: 100%;
        width: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        background-color: rgba(50, 50, 50, 0.8);
    }
    h1{
        color: white;
    }
</style>



