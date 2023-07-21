<script lang='ts'>
    import Widget from "$lib/Widget.svelte";
    import Time from "$lib/widgets/Time.svelte";
    import Notes from "$lib/widgets/Notes.svelte";
    import RaspPi from "$lib/widgets/RaspPi.svelte";
    import Todos from "$lib/widgets/Todos.svelte";
    import Weather from "$lib/widgets/Weather.svelte";

</script>

<div class="space-y-6">
    <div class="flex flex-1 flex-wrap justify-around">
        <Widget/>
        <Time/>
        <Notes/>
    </div>
    <div class="flex flex-1 flex-wrap justify-around"> 
        <RaspPi/>
        <Todos/>
        <Weather/>
    </div>
 
</div>

