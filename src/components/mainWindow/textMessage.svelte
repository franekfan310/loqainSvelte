<script>
    export let pfp;
    export let userName;
    export let rank;
    export let timeStamp;
    export let messageBody;
    export let reactions;
    //loop for displaying reactions for certain messages
</script>
<img src={pfp} alt="no img" width="30" height="30">
<div class="userName">{userName}</div>
<!-- <div class="rank">{rank}</div> -->
<div class="timeStamp">{timeStamp}</div>
<div class="messageBody">{messageBody}</div>