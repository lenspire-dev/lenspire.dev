<script>
    export let value = "";
    export let link = "";
    import Scroller from "./Scroller.svelte";
</script>

<section  class="relative text-center p-32 h-screen bg-white text-black grid justify-center items-center ">

    <div class=" bg-opacity-50 p-16 rounded-3xl ">
        <h1 class="text-7xl md:text-9xl font-bold text-red-800">
            {value}
        </h1>
    </div>
    <Scroller title={false} linkT={link}/>
</section>