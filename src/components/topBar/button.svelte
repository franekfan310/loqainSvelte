<script>
    export let img;
    export let width;
    export let height;
    export let text;
   $: if(text === undefined) {
        text = ""
    }
</script>

<div class="button">
    <img width={width} height={height}  src={img} alt="no img"/>
    <div class="imgText">{text}</div>
</div>