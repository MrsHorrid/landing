<script>
    import block from '$lib/assets/block.png'
	import { fade } from 'svelte/transition';
    
</script>


<div class="p-12 md:flex 2xl:px-[2rem] 3xl:px-[2rem]" transition:fade>
    
    <div class="px-4 flex flex-col justify-center items-center md:items-start xl:px-[8rem] 2xl:px-[10rem]">
        <h1 class="font-bold text-2xl text-center md:text-3xl md:text-left md:mt-8 xl:text-4xl">Blockchain <span class="underline underline-offset-2 decoration-[#713FFF]">the way it was always meant to be.</span></h1>
        <p class="hidden py-8 text-center md:text-left md:block xl:break-words xl:text-xl">Discover Validify, the future of blockchain, where we streamline project success and empower contributors. Our platform enhances efficiency, simplifies standards compliance, and allows users to showcase verified skills. With advanced NFT management and our proprietary blockchain, trust, transparency, and security take center stage. Experience the revolution with Validify.</p>
        <a href="/contact"><button class=" bg-[#713FFF] px-6 py-2 rounded-md mt-5 max-w-lg font-bold text-1xl hover:bg-[#2f1575] ease-in-out duration-200">Contact Us</button></a>
        
    </div>
    <img src={block} alt="" class="w-[42rem]">
    <p class="py-8 text-center md:text-left md:hidden">Discover Validify, the future of blockchain, where we streamline project success and empower contributors. Our platform enhances efficiency, simplifies standards compliance, and allows users to showcase verified skills. With advanced NFT management and our proprietary blockchain, trust, transparency, and security take center stage. Experience the revolution with Validify.</p>
    

</div> 