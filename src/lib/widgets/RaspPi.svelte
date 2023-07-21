<script lang="ts">
    import Widget from "$lib/Widget.svelte";
</script>

<Widget>
    <section slot="header" class="flex justify-between items-center">
        <div class="space-y-1">
            <h2 class="font-semibold text-xl">Raspberry Pi</h2>
            <p class="font-light text-xs">192.168.1.1:2020</p>
        </div>
        <div class="">
            <p class="text-sm text-right">Uptime</p>
            <p class="semibold">49hrs <span class="text-xs font-normal">24m10s</span></p>
        </div>
    </section>
    <div slot="body" class="h-full flex flex-col justify-center space-y-4">
        <div class="flex justify-between items-center">
            <h3 class="w-6 leading-5 text-sm">CPU Heat</h3>
            <p class="text-3xl font-semibold">90°</p>
            <div class="w-44 h-12 bg-neutral-800/40">
            </div>
        </div>
        <div class="flex justify-between">
            <h3 class="w-6 leading-5 text-sm">CPU Usage</h3>
            <p class="text-3xl font-semibold">60%</p>
            <div class="w-44 h-12 bg-neutral-800/40">
            </div>
        </div>
    </div>
</Widget>