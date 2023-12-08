<script>
    export let href='';
    export let icon='';
</script>

<a href={href} target="_blank">
    <svelte:component this={icon} />
</a>