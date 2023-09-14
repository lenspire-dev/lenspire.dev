<script>
    import Section from "$lib/Section.svelte";
    import Scroller from "$lib/Scroller.svelte";
</script>
<main class="font-sans">
<section class="relative p-8 lg:p-32 h-screen bg-white text-black grid  justify-center items-center ">

    <div class=" bg-opacity-50 px-6 py-8 sm:px-9 md:py-10 lg:px-12 lg:py-12 xl:p-16 rounded-tl-3xl rounded-br-3xl  bg-red-200 -mt-16 ">
        <a href="https://www.lenspire.dev">

            <img src="/lenspire.png" alt="Lenspire.dev" >
        </a>

        
    </div>

    <Scroller linkT="/#whoami" />

</section>
<div id="whoami">

    <Section link="/#developer" value="Who am i?" />

</div>
<div id="developer">

    <Section value="I am a 
    <span class='font-light text-gray-800'>full-stack developer.</span>"  link="/#designer"/>

</div>
<div id="designer">

    <Section value="I am a <span class=' font-light text-cyan-400'>designer.</span>"  link="/#producer"/>

</div>
<div id="producer">

    <Section value="I am a <span class='font-light text-purple-600'>music producer.</span>"  link="/#dreams"/>

</div>
<div id="dreams">

    <Section value="I am here to  <span class=' font-light text-pink-400'>make your dreams real.</span>"  link="/#contact"/>

</div>



<div id="contact">

    <Section showArrow={false} value=' Contact me via <a href="https://wa.me/+905444602407" class=" font-light text-green-400">WhatsApp.</a>'  link="/#contact"/>

</div>
</main>