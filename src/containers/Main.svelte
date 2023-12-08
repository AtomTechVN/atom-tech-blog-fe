<script>
    import RightSide from "$containers/RightSide.svelte";
    import LeftSide from "$containers/LeftSide.svelte";
</script>
<div class="bg-gray-100 py-4">
    <div class="grid grid-cols-4 gap-4 w-[1280px] mx-auto">
        <div class="">
            <LeftSide />
        </div>
        <div class="col-span-2">
        </div>
        <div class="">
            <RightSide />
        </div>
    </div>
</div>
