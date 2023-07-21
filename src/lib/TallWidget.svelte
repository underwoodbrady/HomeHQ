<div class="relative rounded-sm w-[400px] h-[536px] bg-widget drop-shadow-md px-8 py-6 flex flex-col overflow-hidden select-none">
    <div class="absolute left-0 top-0 w-full h-full hover:border-2 hover:border-white/70 border-transparent duration-75"></div>
    <slot name="header"/>
    <div class="flex-1">
        <slot name="body" />
    </div>
    <slot name="footer"/>
</div>