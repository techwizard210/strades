<template>
    <div v-if="$device.isDesktop" class="flex grow gap-5 w-[80%] mx-auto">
        <div class="flex flex-col w-[50%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg">
            <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[32px] text-center stroke-shadow">
                <p>Frontend</p>
            </div>
            <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
                <p class="text-[30px]">Nuxt 3</p>
                <p class="text-[30px]">Vue 3</p>
                <p class="text-[30px]">Vite</p>
                <p class="text-[30px]">Tailwind CSS</p>
                <p class="text-[30px]">Axios</p>
                <p class="text-[30px]">Prettier</p>
            </div>
        </div>

        <div class="flex flex-col w-[50%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg">
            <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[32px] text-center stroke-shadow">
                <p>Backend</p>
            </div>
            <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
                <p class="text-[30px]">Django</p>
                <p class="text-[30px]">Tensorflow</p>
                <p class="text-[30px]">Supabase</p>
                <p class="text-[30px]">Postgresql</p>
                <p class="text-[30px]">Python</p>
                <p class="text-[30px]">AWS</p>
            </div>
        </div>
    </div>
    <div v-else class="flex flex-col grow gap-3 w-[100%] mx-auto">
        <div class="flex flex-col w-[85%] mx-auto rounded-br-lg rounded-tl-lg">
            <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[30px] text-center stroke-shadow">
                <p>Frontend</p>
            </div>
            <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
                <p class="text-[25px]">Nuxt 3</p>
                <p class="text-[25px]">Vue 3</p>
                <p class="text-[25px]">Vite</p>
                <p class="text-[25px]">Tailwind CSS</p>
                <p class="text-[25px]">Axios</p>
                <p class="text-[25px]">Prettier</p>
            </div>
        </div>

        <div class="flex flex-col w-[85%] mx-auto rounded-br-lg rounded-tl-lg">
            <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[30px] text-center stroke-shadow">
                <p>Backend</p>
            </div>
            <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
                <p class="text-[25px]">Django</p>
                <p class="text-[25px]">Tensorflow</p>
                <p class="text-[25px]">Supabase</p>
                <p class="text-[25px]">Postgresql</p>
                <p class="text-[25px]">Python</p>
                <p class="text-[25px]">AWS</p>
            </div>
        </div>
    </div>
</template>