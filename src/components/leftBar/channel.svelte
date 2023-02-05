<script>
    export let name;
    export let img;
    name = name.replace(' ', '-');
</script>
<div class="channel">
    <img width=35 height=35 src={img} alt="no image" class="channelImage"/>
    <div class="channelName">{name}</div>
</div>