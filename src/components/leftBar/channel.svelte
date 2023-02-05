<script>
    export let name;
    export let img;
    name = name.replace(' ', '-');
</script>
<img width=35 height=35 src={img} alt="no image" class="channelImage"/>
<div class="channel">{name}</div>