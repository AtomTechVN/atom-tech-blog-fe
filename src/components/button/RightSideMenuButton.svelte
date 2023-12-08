<script>
    export let icon
</script>

<button class="flex gap-2 px-4 py-2 rounded-md hover:bg-indigo-50 hover:text-indigo-900">
        <svelte:component this={icon} class="mr-2"/>
    <slot/>
</button>