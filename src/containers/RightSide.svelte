<script>
    const discuss = [
        {
            id:1,
            title:'Music Monday — What are you listening to? (How-do-you-find-your-music? Edition 🔎)',
            href:'#/a',
            comments:35
        },
        {
            id:2,
            title:'How Do You Organize Your Digital World?',
            href:'#/a',
            comments:3
        }
    ]
</script>

<div class="bg-white border rounded-md border-gray-200">
    <div class="p-4">
        <a class="text-2xl font-bold text-gray-700" href="#/discuss">#discuss</a>
        <br/>
        <span class="text-xs text-gray-500">Discussion threads targeting the whole community</span>
    </div>
    {#each discuss as discus (discus.id)}
        <div class="border-t p-4">
            <a href={discus.href}>
                {discus.title}
            </a>
            <div class="text-gray-500 text-sm mt-2">{discus.comments} comments</div>
        </div>
    {/each}
</div>
