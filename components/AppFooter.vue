<script setup></script>

<template>
  <footer class="w-full py-[30px] bg-gradient-to-t from-[#3E3E3E] mt-20">
    <div
      v-if="$device.isDesktop"
      class="flex justify-between w-[750px] mx-auto text-[20px]"
    >
      <NuxtLink to="/contact" class="hover:opacity-60">
        <p>Refer a friend</p>
      </NuxtLink>
      <NuxtLink to="/contact" class="hover:opacity-60">
        <p>Contact us</p>
      </NuxtLink>
      <NuxtLink to="/terms" class="hover:opacity-60">
        <p>Terms & conditions</p>
      </NuxtLink>
      <NuxtLink to="#">
        <p>© Strades All Rights Reserved 2024</p>
      </NuxtLink>
    </div>
    <div v-else class="flex flex-col gap-5 mx-auto w-[80%] text-[18px]">
        <NuxtLink to="/contact" class="hover:opacity-60">
          <p>Refer a friend</p>
        </NuxtLink>
        <NuxtLink to="/contact" class="hover:opacity-60">
          <p>Contact us</p>
        </NuxtLink>
        <NuxtLink to="/terms" class="hover:opacity-60">
          <p>Terms & conditions</p>
        </NuxtLink>
      <div class="flex justify-between">
        <p>©Strades</p>
        <p>All Rights Reserved 2024</p>
      </div>
    </div>
  </footer>
</template>

<style scoped></style>
