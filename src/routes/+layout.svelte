<script>
    import "../app.css"
</script>

<nav class="  border border-r-0 fixed z-50 px-10 py-6 md:px-16 md:py-8 flex justify-center space-x-10 md:space-x-16 backdrop-blur-sm bg-white bg-opacity-50 top-6 right-0 translate-x-0  h-auto text-xl md:text-2xl font-semibold rounded-l-full  text-red-700 ">
    <a href="/">
        Home    
    </a>
    <a href="/#whoami">
        About
    </a>
    <a href="/#contact">
        Contact
    </a >
    
</nav>

    <slot/>
<style lang="postcss">
    :global(html){
        @apply scroll-smooth;


    }

    /* width */
    :global(::-webkit-scrollbar) {
  width: 10px;
}

/* Track */
:global(::-webkit-scrollbar-track) {
  @apply bg-red-700 transition-all duration-500;
}
/* Track */
:global(::-webkit-scrollbar-track:hover) {
  @apply bg-gray-200 transition-all duration-500;
}

/* Handle */
:global(::-webkit-scrollbar-thumb) {
    @apply bg-white transition-all duration-500;
}

/* Handle on hover */
:global(::-webkit-scrollbar-thumb:hover) {
    @apply bg-red-700 transition-all duration-500;
}
</style>