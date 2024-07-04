<template>
  <div
    v-if="$device.isDesktop"
    class="flex left-2 right-3 justify-between gap-5 fixed z-10 transition-[bottom] duration-400 bottom-[-100%] items-center bg-[#202020] p-[20px] rounded-br-lg rounded-tl-lg font-['MediumFont'] shadow-lg uni-border"
    ref="banner"
  >
    <div>
      <Icon class="text-[70px]" name="mdi:cookie" />
    </div>
    <div class="flex rounded-br-lg rounded-tl-lg font-['SemiBoldItalic']">
      <div class="text-[22px]">
        <p>
          Welcome to <span class="text-[#FFA800] mr-1">Strades!</span> We're glad
          you're here and want you to know that we respect your privacy and your
          right to control how we collect, use, and share your personal
          information. Please read our
          <NuxtLink to="/privacy"
            ><u class="text-[#FFA800]">Privacy Policy</u></NuxtLink
          >
          to learn about our privacy practices.
        </p>
      </div>
    </div>
    <div class="flex gap-5">
      <div
        class="text-[25px] rounded-br-lg rounded-tl-lg bg-gradient-to-r bg-[#484848] px-[15px] py-[5px] hover:cursor-pointer opacity-100 hover:opacity-70 text-[#FFCB45] uni-border"
        @click="acceptCookie"
      >
        Accept
      </div>
      <div
        class="text-[25px] rounded-br-lg rounded-tl-lg bg-gradient-to-r bg-[#484848] px-[15px] py-[5px] hover:cursor-pointer opacity-100 hover:opacity-70"
        @click="close"
      >
        Reject
      </div>
    </div>
  </div>
  <div
    v-else
    class="flex flex-col gap-3 fixed z-10 transition-[bottom] duration-400 bottom-[-100%] bg-[#202020] p-[20px] rounded-br-lg rounded-tl-lg font-['MediumFont'] shadow-lg"
    ref="banner"
  >
    <div class="text-center">
      <Icon class="text-[70px]" name="mdi:cookie" />
    </div>
    <div class="flex rounded-br-lg rounded-tl-lg font-['SemiBoldItalic']">
      <div class="text-[20px]">
        <p>
          Welcome to <span class="text-[#c29b4d]">Strades</span>! We're glad
          you're here and want you to know that we respect your privacy and your
          right to control how we collect, use, and share your personal
          information. Please read our
          <NuxtLink to="/privacy"
            ><u class="text-[#c29b4d]">Privacy Policy</u></NuxtLink
          >
          to learn about our privacy practices.
        </p>
      </div>
    </div>
    <div class="flex gap-1 justify-between w-100">
      <div
        class="text-[22px] basis-1/2 rounded-bl-lg rounded-tr-lg bg-gradient-to-r bg-[#484848] px-[15px] py-[5px] hover:cursor-pointer opacity-100 hover:opacity-70 text-[#eda107] uni-border text-center"
        @click="acceptCookie"
      >
        Accept
      </div>
      <div
        class="text-[22px] basis-1/2 rounded-br-lg rounded-tl-lg bg-gradient-to-r bg-[#484848] px-[15px] py-[5px] hover:cursor-pointer opacity-100 hover:opacity-70 text-center"
        @click="close"
      >
        Reject
      </div>
    </div>
  </div>
</template>

<script setup>
const banner = ref(null);

function show() {
  const bannerElem = banner.value;
  bannerElem.classList.remove("bottom-[-100%]");
  bannerElem.classList.add("bottom-1");
}

function close() {
  const bannerElem = banner.value;
  bannerElem.classList.remove("bottom-1");
  bannerElem.classList.add("bottom-[-100%]");
}

function acceptCookie() {
  const name = useCookie("name");
  name.value = "xxx";
  close();
}

defineExpose({
  show,
  close,
});
</script>
