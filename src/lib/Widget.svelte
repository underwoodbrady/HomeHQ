<div class="rounded-sm w-96 h-64 bg-widget drop-shadow-md p-8 flex flex-col">
    <slot name="header"/>
    <div class="flex-1">
        <slot name="body" />
    </div>
    <slot name="footer"/>
</div>