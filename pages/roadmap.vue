<template>
  <div v-if="$device.isDesktop" class="grow">
    <!-- <div
      class="flex flex-col gap-5 w-[40%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[32px] text-center">
      <p>Strades Documentation</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[40%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[32px] text-center">
      <p>Building the Future of Financial Software</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[40%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[32px] text-center">
      <p>Wikipedia</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[40%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[32px] text-center">
      <p>Strades is a modern platform as an application for traders to connect and track their investments everywhere
        using artificial intelligence. It was founded in 2023 by Maximilien Pelletier.</p>
    </div> -->

    <div class="flex flex-col w-[50%] mx-auto rounded-br-lg rounded-tl-lg">
      <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[32px] text-center">
        <p>Roadmap</p>
      </div>
    </div>

    <div class="flex flex-col w-[50%] mx-auto rounded-br-lg rounded-tl-lg">
      <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[32px] text-center">
        <p>Q1 2024:</p>
      </div>
      <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
        <p class="text-[30px]">Launch Strades beta</p>
        <p class="text-[30px]">Add support for more exchanges and brokers</p>
        <p class="text-[30px]">Improve the user interface and user experience</p>
      </div>
    </div>

    <div class="flex flex-col w-[50%] mx-auto rounded-br-lg rounded-tl-lg">
      <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[32px] text-center">
        <p>Q2 2024:</p>
      </div>
      <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
        <p class="text-[30px]">Launch Strades Pro</p>
        <p class="text-[30px]">Add new features, such as social trading and porfolio management</p>
        <p class="text-[30px]">Improve the user interface and user experience</p>
      </div>
    </div>

    <div class="flex flex-col w-[50%] mx-auto rounded-br-lg rounded-tl-lg">
      <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[32px] text-center">
        <p>Q4 2024:</p>
      </div>
      <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
        <p class="text-[30px]">Launch Strades API</p>
        <p class="text-[30px]">Partner with other financial institutions</p>
        <p class="text-[30px]">Continue to improve and expand the platform</p>
      </div>
    </div>
  </div>
  <div v-else class="grow">
    <!-- <div
      class="flex flex-col gap-5 w-[85%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[25px] text-center">
      <p>Strades Documentation</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[25px] text-center">
      <p>Building the Future of Financial Software</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[25px] text-center">
      <p>Wikipedia</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[25px] text-center">
      <p>Strades is a modern platform as an application for traders to connect and track their investments everywhere
        using artificial intelligence. It was founded in 2023 by Maximilien Pelletier.</p>
    </div> -->

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto p-[20px] rounded-br-lg rounded-tl-lg mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[25px] text-center">
      <p>Roadmap</p>
    </div>

    <div class="flex flex-col w-[85%] mx-auto rounded-br-lg rounded-tl-lg">
      <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[25px] text-center">
        <p>Q1 2024:</p>
      </div>
      <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
        <p class="text-[23px]">Launch Strades beta</p>
        <p class="text-[23px]">Add support for more exchanges and brokers</p>
        <p class="text-[23px]">Improve the user interface and user experience</p>
      </div>
    </div>

    <div class="flex flex-col w-[85%] mx-auto rounded-br-lg rounded-tl-lg">
      <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[25px] text-center">
        <p>Q2 2024:</p>
      </div>
      <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
        <p class="text-[23px]">Launch Strades Pro</p>
        <p class="text-[23px]">Add new features, such as social trading and porfolio management</p>
        <p class="text-[23px]">Improve the user interface and user experience</p>
      </div>
    </div>

    <div class="flex flex-col w-[85%] mx-auto rounded-br-lg rounded-tl-lg">
      <div class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[25px] text-center">
        <p>Q4 2024:</p>
      </div>
      <div class="text-center flex flex-col gap-3 bg-[#202020]/85 p-[10px]">
        <p class="text-[23px]">Launch Strades API</p>
        <p class="text-[23px]">Partner with other financial institutions</p>
        <p class="text-[23px]">Continue to improve and expand the platform</p>
      </div>
    </div>
  </div>
</template>