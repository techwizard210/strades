<template>
  <NuxtParticles id="tsparticles" :options="options" @load="onLoad">
  </NuxtParticles>
  <div
    class="flex flex-col font-['MediumFont'] bg-cover bg-no-repeat text-white min-h-screen"
  >
    <NavigationBar />
    <slot />
    <AppFooter />
    <div
      v-if="$device.isDesktop"
      class="fixed right-10 bottom-20 border-2 border-[white] rounded-br-lg rounded-tl-lg p-[10px] bg-gradient-to-b from-[#474747] from-50% via-[#474747] via-60% to-[#818181] opacity-60 hover:opacity-100"
      @click="scrollTop"
      v-show="isScrolled"
    >
      <Icon
        name="ic:baseline-arrow-upward"
        class="text-[30px] hover:cursor-pointer"
      />
    </div>
  </div>
</template>

<script setup>
const isScrolled = ref(false);

const onLoad = (container) => {
  container.pause();
  setTimeout(() => container.play(), 500);
};

const options = {
  fullScreen: {
    enable: true,
    zIndex: -1,
  },
  background: {
    color: {
      value: "#0e0e0f",
    },
  },
  fpsLimit: 120,
  interactivity: {
    events: {
      onClick: {
        enable: true,
        mode: "push",
      },
      onHover: {
        enable: true,
        mode: "repulse",
      },
    },
    modes: {
      bubble: {
        distance: 400,
        duration: 2,
        opacity: 0.8,
        size: 40,
      },
      push: {
        quantity: 4,
      },
      repulse: {
        distance: 200,
        duration: 0.4,
      },
    },
  },
  particles: {
    color: {
      value: ["#FFA800", "#03dac6"],
    },
    links: {
      color: "random",
      distance: 200,
      enable: true,
      opacity: 0.5,
      width: 1,
    },
    move: {
      direction: "none",
      enable: true,
      outModes: "bounce",
      random: false,
      speed: 2,
      straight: false,
    },
    number: {
      density: {
        enable: true,
      },
      value: 150,
    },
    opacity: {
      value: 0.5,
      random: true,
    },
    shape: {
      type: "circle",
    },
    size: {
      value: { min: 0, max: 4 },
      random: true,
    },
  },
  detectRetina: true,
};

const handleScroll = () => {
  isScrolled.value = window.scrollY > 100;
};

const scrollTop = () => {
  window.scrollTo({ top: 0, behavior: "smooth" });
};

onMounted(() => {
  window.addEventListener("scroll", handleScroll);
});

onUnmounted(() => {
  window.removeEventListener("scroll", handleScroll);
});
</script>
