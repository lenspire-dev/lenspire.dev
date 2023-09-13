<script>
    import "../app.css"
</script>
<!-- 
<nav class="  border md:border-0 fixed z-50 px-6 py-4 md:px-16 md:py-8 flex justify-center space-x-6 md:space-x-16 backdrop-blur-sm bg-white bg-opacity-50 top-6 right-1/2 translate-x-1/2 h-auto text-xl font-semibold rounded-full text-red-700 ">
    <a href="/">
        Home    
    </a>
    <a href="/#whoami">
        About
    </a>
    <a href="/">
        Contact
    </a >
    <a href="/">
        Prices
    </a>
</nav> -->

    <slot/>
<style lang="postcss">
    :global(html){
        @apply scroll-smooth;
    }
</style>