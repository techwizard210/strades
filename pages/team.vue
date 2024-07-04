<template>
  <div v-if="$device.isDesktop" class="grow">
    <div class="mx-auto max-w-[1340px] w-full">
      <div
        class="flex gap-10 w-[90%] mx-auto bg-[#202020]/80 p-[20px] rounded-br-lg rounded-tl-lg items-center mt-[10%] stroke-shadow"
      >
        <div>
          <img
            src="~/assets/images/founder.png"
            class="w-[230px] rounded-full"
            alt="avatar"
          />
        </div>
        <div class="flex flex-col gap-3 grow">
          <div
            class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[35px] text-center rounded-br-lg rounded-tl-lg shadow-md"
          >
            <p>Maximilien Pelletier</p>
          </div>
          <div class="text-center text-[33px]">CEO & Founder</div>
          <div class="mx-[auto] flex justify-center gap-7 text-[2.5rem]">
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

      <div
        class="flex gap-10 w-[90%] mx-auto bg-[#202020]/80 p-[20px] rounded-br-lg rounded-tl-lg items-center mt-[40px] stroke-shadow"
      >
        <div>
          <img
            src="~/assets/images/wizard.png"
            class="w-[230px] rounded-full"
            alt="avatar"
          />
        </div>
        <div class="flex flex-col gap-3 grow">
          <div
            class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[35px] text-center rounded-br-lg rounded-tl-lg shadow-md"
          >
            <p>Ichiro Yamada</p>
          </div>
          <div class="text-center text-[33px]">Developer</div>
          <div class="mx-[auto] flex justify-center gap-7 text-[2.5rem]">
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
    </div>
  </div>
  <div v-else class="grow">
    <div
      class="flex flex-col w-[90%] mx-auto bg-[#202020]/80 px-[10px] py-[30px] rounded-br-lg rounded-tl-lg items-center mt-[20px] stroke-shadow"
    >
        <img
          src="~/assets/images/founder.png"
          class="w-[150px] rounded-full"
          alt="avatar"
        />
      <div class="flex flex-col gap-3 grow w-[95%]">
        <div
          class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[25px] text-center rounded-br-lg rounded-tl-lg shadow-md"
        >
          <p>Maximilien Pelletier</p>
        </div>
        <div class="text-center text-[25px]">CEO & Founder</div>
        <div class="mx-[auto] flex justify-center gap-5 text-[2rem]">
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

    <div
      class="flex flex-col w-[90%] mx-auto bg-[#202020]/80 px-[10px] py-[30px] rounded-br-lg rounded-tl-lg items-center mt-[20px] stroke-shadow"
    >
        <img
          src="~/assets/images/wizard.png"
          class="w-[150px] rounded-full"
          alt="avatar"
        />
      <div class="flex flex-col gap-3 grow w-[95%]">
        <div
          class="mt-5 bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] text-[25px] text-center rounded-br-lg rounded-tl-lg shadow-md"
        >
          <p>Ichiro Yamada</p>
        </div>
        <div class="text-center text-[25px]">Developer</div>
        <div class="mx-[auto] flex justify-center gap-5 text-[2rem]">
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
  </div>
</template>
