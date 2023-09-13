<script>
    import Section from "$lib/Section.svelte";
    import Scroller from "$lib/Scroller.svelte";
</script>
<main>
    <section class="relative p-8 lg:p-32 h-screen bg-white text-black grid  justify-center items-center 
">

    <div class=" bg-opacity-50 px-4 py-6 sm:px-8 md:py-6 lg:px-12 lg:py-8 xl:p-16 rounded-full bg-red-200 -mt-16 ">
        <img src="/lenspire.png" alt="Lenspire.dev" class="">
        
    </div>
    <Scroller linkT="/#whoami" />
</section>
<div id="whoami">
    <Section link="/#developer" value="Who am i?" />

</div>
<div id="developer">
    <Section value="I am a developer."  link="/#designer"/>

</div>
<div id="designer">
    <Section value="I am a designer."  link="/#producer"/>

</div>
<div id="producer">
    <Section value="I am a music producer."  link="/#dreams"/>

</div>
<div id="dreams">

<Section value="I am here to make your dreams real."  link="/"/>
</div>

</main>