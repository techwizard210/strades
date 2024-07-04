<template>
  <div v-if="$device.isDesktop" class="grow">
    <div
      class="mx-auto w-fit border-2 border-[white] rounded-br-lg rounded-tl-lg py-[5px] px-[20px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] mt-20"
    >
      <p class="text-[28px]">About Strades</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow"
      >
        <p>Our mission</p>
      </div>
      <div class="text-center">
        <p class="text-[26px]">
          Building the future of financial Software for everyone
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow"
      >
        <p>Our vision</p>
      </div>
      <div class="text-center">
        <p class="text-[26px]">
          Make trading accessible to anyone willing to invest into their
          furture.
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow" 
      >
        <p>Our values</p>
      </div>
      <div class="text-center flex flex-col gap-3">
        <p class="text-[26px]">Liberty</p>
        <p class="text-[26px]">Transparency</p>
        <p class="text-[26px]">Integrity</p>
        <p class="text-[26px]">Excellence</p>
        <p class="text-[26px]">Teamwork</p>
        <p class="text-[26px]">Acountability</p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow"
      >
        <p>Our history</p>
      </div>
      <div class="text-center flex flex-col gap-3">
        <p class="text-[26px]">
          Founded in 2023 by Maximilien Pelletier, Strades has a rich history of
          innovation...
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow"
      >
        <p>Company's Structure</p>
      </div>
      <div class="text-center flex flex-col gap-3">
        <p class="text-[26px]">
          Our company is currently under construction...
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="w-fit px-[15px] mx-auto text-center p-[5px] text-[28px] border-2 border-[white] rounded-br-lg rounded-tl-lg"
      >
        <p>Location</p>
      </div>
      <div class="text-center">
        <p class="text-[26px]">Paris, France</p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="w-fit px-[15px] mx-auto text-center p-[5px] text-[28px] border-2 border-[white] rounded-br-lg rounded-tl-lg"
      >
        <p>Departments</p>
      </div>
      <div class="text-center flex flex-col gap-3">
        <p class="text-[26px]">Design</p>
        <p class="text-[26px]">Documentation</p>
        <p class="text-[26px]">Testing</p>
        <p class="text-[26px]">Coding</p>
        <p class="text-[26px]">Communication</p>
      </div>
    </div>
  </div>

  <div v-else class="grow">
    <div
      class="mx-auto border-2 w-fit border-[white] rounded-br-lg rounded-tl-lg py-[5px] px-[20px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] mt-5"
    >
      <p class="text-[27px]">About Strades</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[27px] stroke-shadow"
      >
        <p>Our mission</p>
      </div>
      <div class="text-center">
        <p class="text-[25px]">Build the best trading platform for everyone.</p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[27px] stroke-shadow"
      >
        <p>Our vision</p>
      </div>
      <div class="text-center">
        <p class="text-[25px]">
          Make trading accessible to everyone to invest in their furture.
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[27px] stroke-shadow"
      >
        <p>Our values</p>
      </div>
      <div class="text-center flex flex-col gap-3">
        <p class="text-[25px]">Liberty</p>
        <p class="text-[25px]">Transparency</p>
        <p class="text-[25px]">Integrity</p>
        <p class="text-[25px]">Excellence</p>
        <p class="text-[25px]">Teamwork</p>
        <p class="text-[25px]">Acountability</p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="w-[200px] mx-auto text-center p-[5px] text-[27px] border-2 border-[white] rounded-br-lg rounded-tl-lg stroke-shadow"
      >
        <p>Our history</p>
      </div>
      <div class="text-center mt-5">
        <p class="text-[25px]">
          Founded in 2023 by Maximilien Pelletier, Strades has a rich history of
          innovation...
        </p>
      </div>
    </div>
  </div>
</template>
