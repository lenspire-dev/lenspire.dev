<script>
    export let title = true;
    export let linkT = "";
</script>

<a href="{linkT}" class="absolute bottom-16 right-1/2 translate-x-1/2 grid justify-center items-center text-center w-full gap-3">
    {#if title}
    <span class="absolute  right-1/2 translate-x-1/2 bottom-10 font-bold">
        Scroll down
    </span>
    <div class="absolute  right-1/2 translate-x-1/2 border-2 border-red-700 h-12 w-8 rounded-full ">
        <div class="bg-red-700 h-3 w-1 top-3 absolute rounded-full right-1/2 translate-x-1/2">
            
        </div>
    </div>
    {:else}
    <div>
        <svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" fill="currentColor" class="bi bi-chevron-down" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M1.646 4.646a.5.5 0 0 1 .708 0L8 10.293l5.646-5.647a.5.5 0 0 1 .708.708l-6 6a.5.5 0 0 1-.708 0l-6-6a.5.5 0 0 1 0-.708z"/>
          </svg>
    </div>
    {/if}
</a>