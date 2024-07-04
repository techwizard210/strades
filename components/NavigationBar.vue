<template>
  <div class="sticky top-0 backdrop-blur">
    <div
      v-if="$device.isDesktop"
      class="flex items-center justify-between py-2 px-20 w-full h-[100px] z-[3]"
    >
      <NuxtLink to="/" class="opacity-100 hover:opacity-60">
        <div class="flex justify-between items-center py-[5px]">
          <img
            src="~/assets/images/Logo_White.png"
            alt="Company Logo"
            class="w-[50px] flex-none"
          />
          <div class="flex flex-col text-center">
            <img src="~/assets/images/title-gold.png" class="w-[170px]" />
            <img
              src="~/assets/images/InUsWeTrust.png"
              class="w-[140px] mx-auto"
            />
          </div>
        </div>
      </NuxtLink>

      <div
        class="flex items-center rounded-br-lg rounded-tl-lg p-[10px] gap-5 shadow-inner"
      >
        <div
          class="rounded-br-lg rounded-tl-lg p-[4.5px] border-[2px] border-[white] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] opacity-70 hover:opacity-100 hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300"
        >
          <NuxtLink to="/product" class="text-[17px] py-4 px-3"
            >Product</NuxtLink
          >
        </div>
        <div
          class="rounded-br-lg rounded-tl-lg p-[4.5px] border-[2px] border-[white] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] opacity-70 hover:opacity-100 hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300"
        >
          <NuxtLink to="/company" class="text-[17px] py-4 px-3"
            >Company</NuxtLink
          >
        </div>
        <div
          class="rounded-br-lg rounded-tl-lg p-[4.5px] border-[2px] border-[white] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] opacity-70 hover:opacity-100 hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300"
        >
          <NuxtLink to="/documentation" class="text-[17px] py-4 px-3"
            >Documentation</NuxtLink
          >
        </div>
        <div
          class="rounded-br-lg rounded-tl-lg p-[4.5px] border-[2px] border-[white] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] opacity-70 hover:opacity-100 hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300"
        >
          <NuxtLink to="/community" class="text-[17px] py-4 px-3"
            >Community</NuxtLink
          >
        </div>
      </div>
    </div>

    <div
      v-else
      class="flex justify-between items-center p-2 px-[20px] w-full h-[80px] z-[3]"
    >
      <NuxtLink to="/" class="opacity-100 hover:opacity-60">
        <div class="flex gap-1 items-center">
          <img
            src="~/assets/images/Logo_White.png"
            alt="Company Logo"
            class="w-[30px]"
          />
          <img
            src="~/assets/images/title-gold.png"
            alt="Company Logo"
            class="w-[150px]"
          />
        </div>
      </NuxtLink>
      <div
        class="w-fit text-center text-[20px] px-[7px] border-[2px] border-[white] rounded-br-lg rounded-tl-lg"
        @click="openSidebar"
      >
        menu
      </div>
    </div>

    <div
      class="flex flex-col w-0 overflow-x-hidden transition-[width] duration-250 fixed z-10 top-0 right-0 bg-[#111]"
      ref="sidebar"
    >
      <Icon
        name="ic:twotone-close"
        class="text-[40px] text-[white] absolute top-5 right-5"
        @click="closeSidebar"
      />
      <div
        class="mx-auto w-[200px] text-center border-2 border-[white] rounded-br-lg rounded-tl-lg p-[10px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] mt-20"
        @click="handleRoute('product')"
      >
        <p class="text-[25px]">Product</p>
      </div>
      <div
        class="mx-auto w-[200px] text-center border-2 border-[white] rounded-br-lg rounded-tl-lg p-[10px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] mt-10"
        @click="handleRoute('company')"
      >
        <p class="text-[25px]">Company</p>
      </div>
      <div
        class="mx-auto w-[200px] text-center border-2 border-[white] rounded-br-lg rounded-tl-lg p-[10px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] mt-10"
        @click="handleRoute('documentation')"
      >
        <p class="text-[25px]">Documentation</p>
      </div>
      <div
        class="mx-auto w-[200px] text-center border-2 border-[white] rounded-br-lg rounded-tl-lg p-[10px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] mt-10"
        @click="handleRoute('community')"
      >
        <p class="text-[25px]">Community</p>
      </div>
      <div class="flex justify-center gap-3 mt-20">
        <img src="~/assets/images/app-store.png" class="w-[150px]" alt="app-store" />
        <img src="~/assets/images/google-play.png" class="w-[150px]" alt="google-play" />
      </div>
      <div class="mt-10 mx-[auto] flex justify-center gap-6 text-[2.5rem]">
        <a
          href="https://twitter.com/"
          target="_blank"
          rel="noopener noreferrer"
          class="hover:opacity-80"
        >
          <Icon name="simple-icons:x" />
        </a>
        <a
          href="https://youtube.com/JetSetVideo/Strades_info"
          target="_blank"
          rel="noopener noreferrer"
        >
          <Icon name="bi:youtube" class="hover:opacity-80" />
        </a>
        <a
          href="https://facebook.com/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <Icon name="bi:facebook" class="hover:opacity-80" />
        </a>
        <a
          href="https://instagram.com/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <Icon name="bi:instagram" class="hover:opacity-80" />
        </a>
        <a
          href="https://linkedin.com/"
          target="_blank"
          rel="noopener noreferrer"
        >
          <Icon name="bi:linkedin" class="hover:opacity-80" />
        </a>
      </div>
    </div>
  </div>
</template>

<script setup>
const sidebar = ref(null);

function openSidebar() {
  const sidebarElem = sidebar.value;
  sidebarElem.classList.remove("w-0");
  sidebarElem.classList.add("w-screen");
  sidebarElem.classList.add("h-screen");
}

function closeSidebar() {
  const sidebarElem = sidebar.value;
  sidebarElem.classList.remove("w-screen");
  sidebarElem.classList.remove("h-screen");
  sidebarElem.classList.add("w-0");
}

function handleRoute(index) {
  closeSidebar();
  const router = useRouter();
  router.push("/" + index);
}
</script>
