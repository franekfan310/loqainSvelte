<script>
    //import every icon etc.
    import gallery from "../gallery.png";
    import sound from "../static/sound.svg"
    import mic from "../static/mic.svg"
    import NRD from "../static/NRD.png"
    import Button from "./topBar/button.svelte";
	import InvertedButton from "./topBar/invertedButton.svelte";
</script>
<div class="topBar">
<Button width="15" height="15" img={gallery} text="Home"/>
<Button width="30" height="30" img={gallery} text="DMs"/>
<Button width="30" height="30" img={gallery} text="Communities"/>
<Button width="30" height="30" img={sound}/>
<Button width="30" height="30" img={mic}/>
<InvertedButton width="30" height="30" img={NRD} text="NRD#0014"/>
</div>