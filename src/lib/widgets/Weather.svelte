<script lang="ts">
    import Widget from "$lib/Widget.svelte";
</script>

<Widget>
    <section slot="header" class="flex justify-between items-center">
        <h2 class="font font-semibold text-2xl">Today</h2>
        <div class="flex space-x-4">
            <p class="font-light">High <span class="font-semibold ml-1">74°</span></p>
            <p class="font-light">Low <span class="font-semibold ml-1">52°</span></p>

        </div>
    </section>
    <div slot="body" class="h-full flex items-center justify-between">
        <div class="w-16 h-16 bg-white rounded-full"></div>
        <h1 class="font-semibold text-6xl">67°</h1>
        <div class="text-sm">
            <div class="flex items-center space-x-4 justify-between">
                <p class="font-light">Precip</p>
                <p class="font-semibold">0%</p>
            </div>
            <div class="flex items-center space-x-4 justify-between">
                <p class="font-light">Humidity</p>
                <p class="font-semibold">7%</p>
            </div>
            <div class="flex items-center space-x-4 justify-between">
                <p class="font-light">Wind</p>
                <p class="font-semibold">5mph</p>
            </div>
        </div>
    </div>
    <section slot="footer" class="flex justify-between">
        <div class="space-y-1">
            <h4 class="text-center">Thur</h4>
            <p>
                84°
                <span class="font-light ml-1">
                    62°
                </span>
            </p>
        </div>
        <div class="space-y-1">
            <h4 class="text-center">Fri</h4>
            <p>
                87°
                <span class="font-light ml-1">
                    56°
                </span>
            </p>
        </div>
        <div class="space-y-1">
            <h4 class="text-center">Sat</h4>
            <p>
                92°
                <span class="font-light ml-1">
                    61°
                </span>
            </p>
        </div>
        <div class="space-y-1">
            <h4 class="text-center">Sun</h4>
            <p>
                95°
                <span class="font-light ml-1">
                    67°
                </span>
            </p>
        </div>

    </section>
</Widget>