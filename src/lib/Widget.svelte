<script lang="ts">
    let { name, description, style, url, children } = $props();
</script>

<a href={url}>
    <div class="w-48 h-48 rounded-2xl border border-neutral-500 shadow-sm {style} flex flex-col p-5 pb-2.5 transition hover:scale-102">
        <div class="h-full">
            {@render children?.()}
        </div>
        <div class="h-fit">
            <p class="text-2xl font-bold">{name}</p>
            <p class="text-sm">{description}</p>
        </div>
    </div>
</a>