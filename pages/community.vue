<template>
  <div v-if="$device.isDesktop" class="grow">
    <div
      class="w-[57%] mx-auto bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[32px] stroke-shadow"
    >
      <p>Forum</p>
    </div>
    <div
      class="flex flex-col gap-5 w-[55%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit stroke-shadow"
      >
        <p>Messages from Strades</p>
      </div>
      <div class="py-[10px] px-[20px]">
        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">Important informations</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">No-code strategies</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>
      </div>

      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit stroke-shadow"
      >
        <p>Frequently Asked Questions</p>
      </div>
      <div class="py-[10px] px-[20px]">
        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">How to get an affiliation</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">When will Strades be out?</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">What are the ideas driving  the development?</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">How can I install Strades?</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>
      </div>

      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit stroke-shadow"
      >
        <p>Requested Feature</p>
      </div>
      <div class="py-[10px] px-[20px]">
        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">Chart Analysis widget</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">Sentiment predictor</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">No-code strategies</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">An affiliated crypto</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>
      </div>
    </div>

    <div
      class="w-[57%] mx-auto bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[5px] rounded-tr-lg rounded-bl-lg text-[32px] mt-10 stroke-shadow"
    >
      <p class="">Blog</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[55%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit"
      >
        <p>Date: 23/11/2023</p>
      </div>
      <div class="">
        <p class="text-[25px]">
          So far the website presentation is still under construction and most
          of the Figma prototype is getting done. Obviously, things are not
          being done at the rate they were supposed to but life is good and
          that's all that truly matters.
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[55%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit"
      >
        <p>Date: 23/11/2023</p>
      </div>
      <div class="">
        <p class="text-[25px]">
          So far the website presentation is still under construction and most
          of the Figma prototype is getting done. Obviously, things are not
          being done at the rate they were supposed to but life is good and
          that's all that truly matters.
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[55%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit"
      >
        <p>Date: 13/11/2023</p>
      </div>
      <div class="">
        <p class="text-[25px]">
          We are entering the process of creating a prototype for the product.
          This is an "Alpha" stage mainly here to assemble the various part in a
          harmonuous state. It should help us list all the components needed for
          this project to work.
        </p>
      </div>
    </div>
  </div>
  <div v-else class="grow">
    <div
      class="w-[90%] mx-auto bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[2px] rounded-tr-lg rounded-bl-lg text-[28px] stroke-shadow"
    >
      <p>Forum</p>
    </div>
    <div
      class="flex flex-col gap-2 w-[88%] mx-auto bg-[#202020]/85 p-[10px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[25px] w-fit stroke-shadow"
      >
        <p>Messages from Strades</p>
      </div>
      <div class="py-[3px] px-[5px]">
        <Accordion>
          <template v-slot:title>
            <span class="text-[23px]">Important informations</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[23px]">No-code strategies</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>
      </div>

      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit stroke-shadow"
      >
        <p>Frequently Asked Questions</p>
      </div>
      <div class="py-[3px] px-[5px]">
        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">How to get an affiliation</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">When will Strades be out?</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">What are the ideas driving  the development?</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">How can I install Strades?</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>
      </div>

      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[28px] w-fit stroke-shadow"
      >
        <p>Requested Feature</p>
      </div>
      <div class="py-[3px] px-[5px]">
        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">Chart Analysis widget</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">Sentiment predictor</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">No-code strategies</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>

        <Accordion>
          <template v-slot:title>
            <span class="text-[25px]">An affiliated crypto</span>
          </template>
          <template v-slot:content>
            <p>
              ipsum dolor sit amet consectetur adipisicing elit. Quia, porro.
              Non a excepturi, voluptatibus ipsam magnam, eligendi, accusantium
              ipsa quae quis praesentium voluptate saepe ullam sint ea itaque
              consectetur impedit?
            </p>
          </template>
        </Accordion>
      </div>
    </div>

    <div
      class="w-[90%] mx-auto bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] py-[2px] text-[28px] rounded-tr-lg rounded-bl-lg mt-10 stroke-shadow"
    >
      <p class="">Blog</p>
    </div>

    <div
      class="flex flex-col gap-5 w-[88%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[25px] w-fit"
      >
        <p>Date: 23/11/2023</p>
      </div>
      <div class="">
        <p class="text-[20px]">
          So far the website presentation is still under construction and most
          of the Figma prototype is getting done. Obviously, things are not
          being done at the rate they were supposed to but life is good and
          that's all that truly matters.
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[88%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[25px] w-fit"
      >
        <p>Date: 23/11/2023</p>
      </div>
      <div class="">
        <p class="text-[20px]">
          So far the website presentation is still under construction and most
          of the Figma prototype is getting done. Obviously, things are not
          being done at the rate they were supposed to but life is good and
          that's all that truly matters.
        </p>
      </div>
    </div>

    <div
      class="flex flex-col gap-5 w-[88%] mx-auto bg-[#202020]/85 p-[20px] rounded-br-lg rounded-tl-lg mt-5"
    >
      <div
        class="bg-gradient-to-r from-[#484848] via-[#686868] to-[#AEAEAE] px-[20px] rounded-tl-lg rounded-br-lg text-[25px] w-fit"
      >
        <p>Date: 13/11/2023</p>
      </div>
      <div class="">
        <p class="text-[20px]">
          We are entering the process of creating a prototype for the product.
          This is an "Alpha" stage mainly here to assemble the various part in a
          harmonuous state. It should help us list all the components needed for
          this project to work.
        </p>
      </div>
    </div>
  </div>
</template>
<script setup>
const items = [
  {
    label: "Getting Started",
    defaultOpen: false,
    content:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.",
  },
  {
    label: "Theming",
    content:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.",
  },
  {
    label: "Layouts",
    content:
      "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed neque elit, tristique placerat feugiat ac, facilisis vitae arcu. Proin eget egestas augue. Praesent ut sem nec arcu pellentesque aliquet. Duis dapibus diam vel metus tempus vulputate.",
  },
];
</script>
