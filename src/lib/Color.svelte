<script>
    export let color;
</script>

<div style="background:{color}">
    <p>Color : {color}</p>
</div>

<style>
    div {
   	 box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.5);
   	 padding: 0.5em;
   	 width: 120px;
   	 margin: 0.5em auto;
   	 border-radius: 5px;
   	 text-align: center;
   	 font-weight: bold;
    }
    p {
   	 margin: 0;
    }
</style>

