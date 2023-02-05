<script>
	import Channel from "./leftBar/channel.svelte";
        import drop from "../static/Union.svg"
        import pin from "../pin.svg"
	import InvertedButton from "./topBar/invertedButton.svelte";
</script>
<div class="leftBar">
        <div class="important">
                <InvertedButton width="15" height="9" img={drop} text="Important"/>
                <Channel name={"Loqa Rules"} img={pin}/>
                <Channel name={"Official Announcements"} img={pin}/>
        </div>
        <div class="happening">
                <InvertedButton width="15" height="9" img={drop} text="What's happening"/>
                <Channel name={"Favorite Channels"} img={pin}/>
                <Channel name={"Friend activity"} img={pin}/>
                <Channel name={"Popular recently"} img={pin}/>
        </div>
        <div class="pinnedComunities">
                <InvertedButton width="15" height="9" img={drop} text="Pinned communities"/>
                <Channel name={"Negative Zero HUB"} img={pin}/>
                <Channel name={"Concept Central"} img={pin}/>
                <Channel name={"Meme FM"} img={pin}/>
        </div>
        <div class="pinneddms">
                <InvertedButton width="15" height="9" img={drop} text="Pinned DMs and group chats"/>
                <Channel name={"Jephyr"} img={pin}/>
                <Channel name={"Iridescentkiwi"} img={pin}/>
                <Channel name={"WiiUGamerJ"} img={pin}/>
                <Channel name={"Corion"} img={pin}/>
                <Channel name={"DormentCoder"} img={pin}/>
                <Channel name={"Luca"} img={pin}/>
                <Channel name={"MajsterKotel"} img={pin}/>
                <Channel name={"Krogucci"} img={pin}/>
        </div>
        <!-- <Channel name={"leftchannel1"} img={"https://upload.wikimedia.org/wikipedia/commons/thumb/6/6d/Windows_Settings_app_icon.png/768px-Windows_Settings_app_icon.png"} /> -->
</div>