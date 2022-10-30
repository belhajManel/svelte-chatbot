<script>
    export let happyScore = 1;
    export let size = 1;
    
    const faceList = ['🤬', '😡', '😭', '🙁', '😕',  '😐', '🙂', '😀', '😄', '😊', '😘'];
    $: index = happyScore + 4;
</script>

<div style="font-size: {size}em" >
    {faceList[index]}
</div>

<style>
	div {
		padding-top: 40px
	}
 
</style>