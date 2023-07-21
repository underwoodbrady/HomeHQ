<script lang="ts">
    import Widget from "$lib/Widget.svelte";
</script>

<Widget>
    <section slot="header" class="mb-5 flex justify-between items-center">
        <h2 class="text-lg font-semibold">Daily Todos</h2>
        <p class="text-sm font-light">Menu</p>
    </section>
    <div slot="body" class="ml-1 space-y-2">
        <div class="flex space-x-3 items-center">
            <div class="w-4 h-4 rounded-sm border bg-white border-white"></div>
            <p class="text-sm">Do Laundry</p>
        </div>
        <div class="flex space-x-3 items-center">
            <div class="w-4 h-4 rounded-sm border border-white"></div>
            <p class="text-sm">Pay for school</p>
        </div>
        <div class="flex space-x-3 items-center">
            <div class="w-4 h-4 rounded-sm border border-white"></div>
            <p class="text-sm">Pick up groceries</p>
        </div>
        <div class="flex space-x-3 items-center">
            <div class="w-4 h-4 rounded-sm border border-white"></div>
            <p class="text-sm">Finish this project</p>
        </div>
    </div>
    <section slot="footer">
        <p class="text-sm font-light">1/4 complete</p>
    </section>
</Widget>