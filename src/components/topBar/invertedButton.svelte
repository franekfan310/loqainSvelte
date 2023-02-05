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
    <div class="imgText">{text}</div>
    <img width={width} height={height}  src={img} alt="no img"/>
</div>