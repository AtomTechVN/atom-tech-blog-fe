<script>
  import SearchIcon from "$icons/SearchIcon.svelte";
</script>

<div class="border-b-2">
  <div class="flex justify-between items-center py-3 w-[1280px] mx-auto">
    <div class="flex gap-4">
      <img
        src="https://dev-to-uploads.s3.amazonaws.com/uploads/logos/resized_logo_UQww2soKuUsjaOGNB38o.png"
        alt="Logo"
        class="w-14"
      />
      <div
        class="border-gray-200 border rounded-md focus-within:border-indigo-700 flex items-center pl-2 py-[1px] pr-[1px]"
      >
        <input type="text" placeholder="Search..." class="focus:outline-none" />
        <button class="hover:bg-indigo-50 h-full px-2 rounded-md">
          <SearchIcon />
        </button>
      </div>
    </div>
    <div class="flex gap-4">
      <button
        class="rounded-md hover:bg-indigo-50 hover:text-indigo-900 px-4 py-2"
        >Log in</button
      >
      <button
        class="border border-indigo-700 rounded-md px-4 py-2 text-indigo-700 font-medium hover:bg-indigo-700 hover:text-white"
        >Create account</button
      >
    </div>
  </div>
</div>
