<template>
  <div v-if="$device.isDesktop" class="grow">
    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020] p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[32px] stroke-shadow"
      >
        <p>Contact us</p>
      </div>
      <div class="text-center">
        <p class="text-[30px] font-['SemiBoldItalic']">
          Contact our support team for any inquries
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[45%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div class="flex justify-center gap-3">
        <input
          class="basis-1/3 italic border-[1px] border-[white] text-[20px] px-[20px] bg-transparent placeholder-[white] placeholder-opacity-50 rounded-br-lg rounded-tl-lg hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300 hover:text-white p-[10px]"
          placeholder="your-email@address.com"
        />
        <input
          class="basis-2/3 italic border-[1px] border-[white] text-[20px] px-[20px] bg-transparent placeholder-[white] placeholder-opacity-50 rounded-br-lg rounded-tl-lg hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300 hover:text-white p-[10px]"
          placeholder="Subject of your inquiry"
        />
      </div>
      <textarea
        class="p-[20px] italic placeholder-[white] placeholder-opacity-50 rounded-br-lg rounded-tl-lg hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration text-[23px] bg-[#3b3b3b] min-h-[200px]"
        placeholder="Write your text here..."
      ></textarea>
      <div class="flex flex-row-reverse">
        <div
          class="rounded-br-lg rounded-tl-lg py-[3px] px-[25px] bg-gradient-to-r from-[#606060] from-50% via-[#474747] via-60% to-[#818181] hover:text-[#FFA800] hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300 cursor-pointer stroke-shadow"
          @click=""
        >
          <p class="text-[20px]">Send</p>
        </div>
      </div>
    </div>
  </div>

  <div v-else class="grow">
    <div
      class="flex flex-col gap-3 w-[90%] mx-auto bg-[#202020] p-[10px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow"
      >
        <p>Contact us</p>
      </div>
      <div class="text-center px-[20px] py-[5px]">
        <p class="text-[25px] font-['SemiBoldItalic']">
          Contact our support team for any inquries
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[90%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div class="flex flex-col gap-3">
        <input
          class="basis-1/3 italic border-[1px] border-[white] text-[20px] px-[20px] bg-transparent placeholder-[white] placeholder-opacity-50 rounded-br-lg rounded-tl-lg hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300 hover:text-white p-[10px]"
          placeholder="your-email@address.com"
        />
        <input
          class="basis-2/3 italic border-[1px] border-[white] text-[20px] px-[20px] bg-transparent placeholder-[white] placeholder-opacity-50 rounded-br-lg rounded-tl-lg hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300 hover:text-white p-[10px]"
          placeholder="Subject of your inquiry"
        />
      </div>
      <textarea
        class="p-[20px] italic placeholder-[white] placeholder-opacity-50 rounded-br-lg rounded-tl-lg hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration text-[23px] bg-[#3b3b3b] min-h-[200px]"
        placeholder="Write your text here..."
      ></textarea>
      <div class="flex flex-row-reverse">
        <div
          class="rounded-br-lg rounded-tl-lg py-[3px] px-[25px] bg-gradient-to-r from-[#606060] from-50% via-[#474747] via-60% to-[#818181] hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300 cursor-pointer"
          @click=""
        >
          <p class="text-[20px] hover:text-[#FFA800]">Send</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
textarea:focus,
input:focus {
  outline: none;
}
</style>
