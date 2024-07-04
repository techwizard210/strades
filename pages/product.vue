<template>
  <div v-if="$device.isDesktop" class="grow">
    <div
      class="flex flex-col gap-5 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow"
      >
        <p>Available on every platform</p>
      </div>
      <div class="text-center">
        <p class="text-[27px]">Google / Apple / Windows / Mac / Web</p>
      </div>
      <div class="flex justify-center gap-5">
        <img src="~/assets/images/app-store.png" class="" alt="app-store" />
        <img src="~/assets/images/google-play.png" alt="google-play" />
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
        <p class="text-[27px]">
          Make trading accessible to everyone to invest in their furture.
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
        <p class="text-[27px]">Liberty</p>
        <p class="text-[27px]">Transparency</p>
        <p class="text-[27px]">Integrity</p>
        <p class="text-[27px]">Excellence</p>
        <p class="text-[27px]">Teamwork</p>
        <p class="text-[27px]">Acountability</p>
      </div>
    </div>

    <div
      class="flex flex-col gap-3 w-[70%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[28px] text-center stroke-shadow"
      >
        <p>Pricing</p>
      </div>
      <div
        class="text-center flex flex-col gap-3 text-[27px] font-['SemiBoldItalic']"
      >
        <div class="flex gap-3 py-0 px-5">
          <div
            class="basis-1/3 flex flex-col gap-5 border-2 border-[white] rounded-br-lg rounded-tl-lg p-[20px]"
          >
            <span
              class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
              >Free For All</span
            >
            <p>Access all features for free...</p>
            <p>But in limited quantities</p>
          </div>
          <div
            class="basis-1/3 flex flex-col gap-5 border-[white] border-2 rounded-br-lg rounded-tl-lg p-[20px]"
          >
            <span
              class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
              >Premium Membership</span
            >
            <p>Buy, offer and trade our special extensions and gifts</p>
          </div>
          <div
            class="basis-1/3 flex flex-col gap-5 border-[white] border-2 rounded-br-lg rounded-tl-lg p-[20px]"
          >
            <span
              class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
              >Memberships Premium</span
            >
            <p>10€/month:</p>
            <p>Get access to the private mode for your account</p>
          </div>
        </div>
        <div
          class="flex flex-col gap-5 border-[white] border-2 rounded-br-lg rounded-tl-lg mt-3 p-[20px]"
        >
          <span
            class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
            >Refer a Friend</span
          >
          <p>
            Invite your relatives to join the Strades experience and earn free
            coins or memberships
          </p>
        </div>
      </div>
    </div>
  </div>

  <div v-else class="grow">
    <div
      class="flex flex-col gap-5 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[23px] text-center stroke-shadow"
      >
        <p>Available on every platform</p>
      </div>
      <div class="text-center">
        <p class="text-[22px]">Google / Apple / Windows / Mac / Web</p>
      </div>
      <div class="flex justify-center gap-3 px-[20px]">
        <img
          src="~/assets/images/app-store.png"
          class="w-[150px]"
          alt="app-store"
        />
        <img
          src="~/assets/images/google-play.png"
          class="w-[150px]"
          alt="google-play"
        />
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[23px] text-center stroke-shadow"
      >
        <p>Our vision</p>
      </div>
      <div class="text-center">
        <p class="text-[22px]">
          Make trading accessible to everyone to invest in their furture.
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[23px] text-center stroke-shadow"
      >
        <p>Our values</p>
      </div>
      <div class="text-center flex flex-col gap-3">
        <p class="text-[22px]">Liberty</p>
        <p class="text-[22px]">Transparency</p>
        <p class="text-[22px]">Integrity</p>
        <p class="text-[22px]">Excellence</p>
        <p class="text-[22px]">Teamwork</p>
        <p class="text-[22px]">Acountability</p>
      </div>
    </div>

    <div
      class="flex flex-col gap-3 w-[85%] mx-auto bg-[#202020]/85 p-[15px] rounded-br-lg rounded-tl-lg mt-10"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[23px] text-center stroke-shadow"
      >
        <p>Pricing</p>
      </div>
      <div
        class="text-center flex flex-col gap-3 text-[22px] font-['SemiBoldItalic']"
      >
        <div
          class="basis-1/3 flex flex-col gap-5 border-2 border-[white] rounded-br-lg rounded-tl-lg p-[20px]"
        >
          <span
            class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
            >Free For All</span
          >
          <p>Access all features for free...</p>
          <p>But in limited quantities</p>
        </div>
        <div
          class="basis-1/3 flex flex-col gap-5 border-[white] border-2 rounded-br-lg rounded-tl-lg p-[20px]"
        >
          <span
            class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
            >Premium Membership</span
          >
          <p>Buy, offer and trade our special extensions and gifts</p>
        </div>
        <div
          class="basis-1/3 flex flex-col gap-5 border-[white] border-2 rounded-br-lg rounded-tl-lg p-[20px]"
        >
          <span
            class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
            >Memberships Premium</span
          >
          <p>10€/month:</p>
          <p>Get access to the private mode for your account</p>
        </div>
        <div
          class="flex flex-col gap-5 border-[white] border-2 rounded-br-lg rounded-tl-lg mt-3 p-[20px]"
        >
          <span
            class="bg-gradient-to-r from-[#FFA800] via-[#FFCB45] to-[#FFA800] inline-block text-transparent bg-clip-text font-['MediumFont'] font-bold tracking-wider"
            >Refer a Friend</span
          >
          <p>
            Invite your relatives to join the Strades experience and earn free
            coins or memberships
          </p>
        </div>
      </div>
    </div>
  </div>
</template>
