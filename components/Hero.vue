<template>
  <div v-if="$device.isDesktop">
    <img
      loading="lazy"
      src="~/assets/images/InvestmentClockDall.png"
      alt="InvestmentClockDall"
      class="w-[300px] mx-[auto] mt-20"
    />
    <div
      class="mt-20 mx-[auto] flex justify-center gap-7 text-[2.8rem] pt-[5px]"
    >
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
      <a href="https://facebook.com/" target="_blank" rel="noopener noreferrer">
        <Icon name="bi:facebook" class="hover:opacity-80" />
      </a>
      <a
        href="https://instagram.com/"
        target="_blank"
        rel="noopener noreferrer"
      >
        <Icon name="bi:instagram" class="hover:opacity-80" />
      </a>
      <a href="https://linkedin.com/" target="_blank" rel="noopener noreferrer">
        <Icon name="bi:linkedin" class="hover:opacity-80" />
      </a>
    </div>
    <div
      class="mt-20 mx-[auto] flex flex-col gap-3 bg-gradient-to-r from-[#606060] from-50% via-[#474747] via-60% to-[#818181] w-[800px] rounded-br-lg rounded-tl-lg p-[10px] text-center stroke-shadow"
    >
      <p class="text-[25px] font-['Ethnocentric'] italic">JOIN OUR BETA NOW:</p>
      <div class="flex gap-2 justify-center items-center">
        <UCheckbox color="yellow" v-model="selected" />
        <p class="text-[20px]">I accept to subscribe to the newsletter</p>
      </div>
      <div
        class="w-[450px] flex rounded-tr-lg rounded-bl-lg border-2 border-[#FFA800] px-[5px] py-[6px] mx-auto"
      >
        <input
          class="basis-3/4 italic text-[20px] px-[20px] bg-transparent focus:border-none placeholder-[#FFCB45] placeholder-opacity-50"
          placeholder="your-email@address.com"
        />
        <div
          class="text-[25px] text-[#FFA800] basis-1/4 rounded-br-lg rounded-tl-lg bg-[#202020] p-[5px] cursor-pointer hover:rounded-bl-lg hover:rounded-tr-lg hover:rounded-br-none hover:rounded-tl-none transition-all duration-300 hover:text-white"
        >
          <span
            class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text hover:text-white transition-all duration-300"
            >Send</span
          >
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-2 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[32px] text-[#FFA800] font-bold tracking-wider text-center box-title rounded-tr-lg rounded-bl-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text"
          >AI-powered platform</span
        >
      </div>
      <div class="flex flex-row-reverse gap-3 items-center">
        <img
          src="~/assets/images/IconCapitalAllocationBrainAIDallE.png"
          class="w-[156px] h-[156px] rounded-tr-lg rounded-bl-lg"
          alt="IconCapitalAllocationBrainAIDallE"
        />
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[30px] stroke-shadow"
          >
            <p>Optimal Management of your Capital</p>
          </div>
          <div class="text-[28px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>Optimize your capital allocation with your AI</p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-2 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10 uni-border font-['MediumFont']"
    >
      <div
        class="text-[32px] text-[#FFA800] font-bold tracking-wider text-center box-title rounded-tr-lg rounded-bl-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text"
          >Social Network for Finance</span
        >
      </div>
      <div class="flex gap-3 items-center">
        <img
          src="~/assets/images/CoinClockGoldenDallE.png"
          class="rounded-tr-lg w-[150px] rounded-bl-lg"
          alt="CoinClockGoldenDallE"
        />
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] py-[2px] text-center rounded-tr-lg rounded-bl-lg text-[30px] stroke-shadow"
          >
            <p>Invest in yourself and your entourage</p>
          </div>
          <div class="text-[28px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>
              Keep track of your investments on a daily basis and share your
              findings with your relatives.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-2 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[32px] text-[#FFA800] font-bold tracking-wider text-center box-title rounded-tr-lg rounded-bl-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text"
          >Portfolio Manager</span
        >
      </div>
      <div class="flex flex-row-reverse gap-3 items-center">
        <img
          src="~/assets/images/GoldenInfinityClocksComparingDallE.png"
          class="w-[156px] h-[156px] rounded-tr-lg rounded-bl-lg"
          alt="GoldenInfinityClocksComparingDallE"
        />
        <div
          class="flex grow flex-col rounded-br-lg rounded-tl-lg stroke-shadow"
        >
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[30px] stroke-shadow"
          >
            <p>Compare or Combine your Portfolios</p>
          </div>
          <div class="text-[28px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>Mix your performance with your friends or the best traders.</p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-2 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[32px] text-[#FFA800] font-bold tracking-wider text-center box-title rounded-tr-lg rounded-bl-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text"
          >No-Code Editor</span
        >
      </div>
      <div class="flex gap-3 items-center">
        <img
          src="~/assets/images/iconGeneratorBacktestDallE.png"
          class="w-[200px] rounded-tr-lg rounded-bl-lg"
          alt="iconGeneratorBacktestDallE"
        />
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[30px] stroke-shadow"
          >
            <p>Build, test, share or rent strategies</p>
          </div>
          <div class="text-[28px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>
              Create complex Backtest strategies with minimal inputs. Then pass
              them from their Backtest forms into Livetest.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-2 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[32px] text-center font-bold tracking-wider box-title rounded-tr-lg rounded-bl-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text"
          >Available on all devices</span
        >
      </div>
      <div class="flex gap-3 items-center">
        <img
          src="~/assets/images/iconFromMobileToDesktopDallE.png"
          class="w-[150px] h-[150px] rounded-tr-lg rounded-bl-lg"
          alt="iconFromMobileToDesktopDallE"
        />
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[30px] stroke-shadow"
          >
            <p>Track your investments everywhere at anytime</p>
          </div>
          <div class="text-[28px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>From your phone to your computer</p>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div v-else>
    <div
      class="mx-auto w-fit border-2 border-[white] rounded-br-lg rounded-tl-lg p-[10px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] mt-[30%]"
    >
      <p class="text-[25px] font-['Ethnocentric'] italic">IN US WE TRUST</p>
    </div>

    <div class="text-center mt-5 text-[30px]">
      The First Intelligent Social Trading Platform
    </div>

    <div class="mt-5 mx-[auto] flex justify-center gap-6 text-[2.5rem]">
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
      <a href="https://facebook.com/" target="_blank" rel="noopener noreferrer">
        <Icon name="bi:facebook" class="hover:opacity-80" />
      </a>
      <a
        href="https://instagram.com/"
        target="_blank"
        rel="noopener noreferrer"
      >
        <Icon name="bi:instagram" class="hover:opacity-80" />
      </a>
      <a href="https://linkedin.com/" target="_blank" rel="noopener noreferrer">
        <Icon name="bi:linkedin" class="hover:opacity-80" />
      </a>
    </div>

    <div
      class="flex flex-col gap-4 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-40 uni-border"
    >
      <div
        class="text-[27px] text-center box-title rounded-tl-lg rounded-br-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-bold tracking-wider"
          >AI-powered platform</span
        >
      </div>
      <div class="flex flex-row-reverse gap-3 items-center">
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[23px]"
          >
            <p>Optimal Management of your Capital</p>
          </div>
          <div class="text-[22px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>Optimize your capital allocation with your AI</p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-4 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[27px] text-center box-title rounded-tl-lg rounded-br-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-bold tracking-wider"
          >Social Network for Finance</span
        >
      </div>
      <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
        <div
          class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] py-[2px] text-center rounded-tr-lg rounded-bl-lg text-[23px]"
        >
          <p>Invest in yourself and your entourage</p>
        </div>
        <div class="text-[22px] text-center p-[10px] font-['SemiBoldItalic']">
          <p>
            Keep track of your investments on a daily basis and share your
            findings with your relatives.
          </p>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-4 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[27px] text-center box-title rounded-tl-lg rounded-br-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-bold tracking-wider"
          >Portfolio Manager</span
        >
      </div>
      <div class="flex flex-row-reverse gap-3 items-center">
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[23px]"
          >
            <p>Compare or Combine your Portfolios</p>
          </div>
          <div class="text-[22px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>Mix your performance with your friends or the best traders.</p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-4 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[27px] text-center box-title rounded-tl-lg rounded-br-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-bold tracking-wider"
          >No-Code Editor</span
        >
      </div>
      <div class="flex gap-3 items-center">
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[23px]"
          >
            <p>Build, test, share or rent strategies</p>
          </div>
          <div class="text-[22px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>
              Create complex Backtest strategies with minimal inputs. Then pass
              them from their Backtest forms into Livetest.
            </p>
          </div>
        </div>
      </div>
    </div>

    <div
      class="flex flex-col gap-4 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10 uni-border"
    >
      <div
        class="text-[27px] text-center box-title rounded-tl-lg rounded-br-lg"
      >
        <span
          class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-bold tracking-wider"
          >Available on all devices</span
        >
      </div>
      <div class="flex gap-3 items-center">
        <div class="flex grow flex-col rounded-br-lg rounded-tl-lg">
          <div
            class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-center rounded-tr-lg rounded-bl-lg text-[23px]"
          >
            <p>Track your investments everywhere at anytime</p>
          </div>
          <div class="text-[22px] text-center p-[10px] font-['SemiBoldItalic']">
            <p>From your phone to your computer</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
const selected = ref(false);
</script>

<style scoped>
textarea:focus,
input:focus {
  outline: none;
}
.checkbox-container input:checked ~ .checkmark {
  background-color: red;
}
</style>
