<script>
    import Widget from "$lib/Widget.svelte";
    import { SiDiscord, SiMedium, SiTelegram, SiX } from "@icons-pack/svelte-simple-icons";
</script>

<main class="min-w-screen inter min-h-screen text-white max-h-full p-5 flex justify-center pattern-boxes pattern-neutral-800 pattern-bg-neutral-900 pattern-size-4 pattern-opacity-100">
    <div class="app w-full md:w-4/5 flex flex-col md:flex-row gap-2">
        <div class="profile w-full h-[96vh] md:w-1/2 md:h-full p-5 pt-[12%] flex flex-col gap-4 bg-gray-800/30 rounded-4xl backdrop-blur-[2px] border border-gray-500">
            <div class="profile-picture w-24 aspect-square rounded-full bg-white"><img alt="logo" src="https://pbs.twimg.com/profile_images/1891787638966771712/-1WC4kAO_x96.jpg" class="rounded-full"></div>
            <div class="flex flex-row gap-5 flex-wrap">
                <p class="text-6xl w-fit font-bold">0xmateo</p>
                <div class="flex flex-1 flex-row gap-3 w-full items-center md:mt-3">
                    <a href="https://x.com/ludohacker">
                        <SiX size={32}/>
                    </a>
                    <a href="https://t.me/ludohacker5">
                        <SiTelegram size={32}/>
                    </a>
                    <a href="https://discordapp.com/users/795590409619374090">
                        <SiDiscord size={32}/>
                    </a>
                    <a href="https://medium.com/@mateoguy">
                        <SiMedium size={32}/>
                    </a>
                </div>
            </div>
            <p class="text-lg md:text-xl ml-1">Web3 Explorer | Community Builder | Diving into crypto & beyond</p>
            <div class="roles mt-[12%] font-semibold text-lg md:text-xl ml-1">
                <p class="text-lg text-gray-300 font-normal">My roles:</p>
                <div class="flex flex-row items-center">
                    <img src="Injective Symbol - White.png" alt="Logo" class="w-8 h-8 mx-2 object-contain">
                    <p class="mt-1">Warrior of Injective</p>
                </div>
                <div class="flex flex-row items-center">
                    <img src="swapcoffee.png" alt="Logo" class="w-8 h-8 mx-2 object-contain">
                    <p class="mt-1">swap.coffee Ambassador</p>
                </div>
                <div class="flex flex-row items-center">
                    <img src="stonfi.png" alt="Logo" class="w-8 h-8 mx-2 object-contain">
                    <p class="mt-1">STON.fi Ambassador</p>
                </div>
            </div>
        </div>
        <div class="widgets w-full h-full md:w-1/2 bg-gray-800/30 rounded-4xl backdrop-blur-[2px] border border-gray-500 p-8 mx-auto grid max-w-full grid-cols-1 gap-4 md:auto-rows-[12rem] md:grid-cols-3">
            <Widget name="Post" description="Post" style="bg-black" url="https://x.com/ludohacker/status/1894779874620985391"><SiX size={58}/></Widget>
            <Widget name="Post" description="Post" style="bg-black" url="https://x.com/ludohacker/status/1907719404969656576"><SiX size={58}/></Widget>
            <Widget name="Post" description="Post" style="bg-black" url="https://x.com/ludohacker/status/1907131239611469941"><SiX size={58}/></Widget>
            <Widget name="Post" description="Post" style="bg-black" url="https://x.com/ludohacker/status/1907012662182936968"><SiX size={58}/></Widget>
            <Widget name="Post" description="Post" style="bg-black" url="https://x.com/ludohacker/status/1892326840729293246"><SiX size={58}/></Widget>
            <Widget name="Post" description="Post" style="bg-black" url="https://x.com/ludohacker/status/1891831540436414541"><SiX size={58}/></Widget>
        </div>
    </div>
</main>