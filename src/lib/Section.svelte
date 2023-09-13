<script>
    export let value = "";
    export let link = "";
    export let showArrow = true ;
    import Scroller from "./Scroller.svelte";
</script>

<section  class="relative text-center p-32 h-screen  bg-white text-black grid justify-center items-center ">

    <div class=" bg-opacity-50  rounded-3xl ">
        <h1 class="text-6xl sm:text-7xl md:text-8xl lg:text-9xl font-bold text-red-800">
            {@html value}
        </h1>
    </div>
    <Scroller {showArrow} title={false} linkT={link}/>
</section>