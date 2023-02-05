<script>
	import Button from "./topBar/button.svelte";
    import plus from "../static/plus.svg"
    import send from "../static/send.svg"
</script>

<Button img={plus} width="30" height="30"/> 
<input type="text" placeholder="Say something"/>
<Button img={send}/>