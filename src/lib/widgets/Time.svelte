<script lang="ts">
    import Widget from "$lib/Widget.svelte";
    import ResponsiveWidget from '$lib/ResponsiveWidget.svelte';
    //Show sunset and sunrise time?
</script>

<ResponsiveWidget>
    <section slot="header" class="flex justify-between items-center">
        <h4 class="text-lg">7/20</h4>
        <div>
            <h3 class="">Work</h3>
        </div>
    </section>
    <div slot="body" class="flex justify-center items-center h-full">
        <h1 class="text-7xl tracking-wider font-semibold">6:54</h1> 
    </div>
    <section slot="footer" class="flex justify-center">
            <p class="font-thin italic">"let yourself heal" - <span class="font-normal not-italic">mo bamba</span></p>
    </section>
</ResponsiveWidget>