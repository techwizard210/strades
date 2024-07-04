<template>
  <div>
    <div
      @click="toggleAccordion()"
      class="flex justify-between items-center space-x-3 text-[20px] p-[10px] cursor-pointer hover:opacity-80"
      :aria-expanded="isOpen"
      :aria-controls="`collapse${_uid}`"
    >
      <slot name="title" />
      <svg
        class="w-3 transition-all duration-200 transform hover:opacity-80"
        :class="{
          'rotate-180': isOpen,
          'rotate-0': !isOpen,
        }"
        fill="none"
        stroke="currentColor"
        xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 16 10"
        aria-hidden="true"
      >
        <path
          d="M15 1.2l-7 7-7-7"
          stroke-width="2"
          stroke-linecap="round"
          stroke-linejoin="round"
        />
      </svg>
    </div>
    <div class="transition-all duration-200 py-[10px] px-[10px] text-[20px]" v-show="isOpen" :id="`collapse${_uid}`">
      <slot name="content" />
    </div>
  </div>
</template>

<script setup>
const isOpen = ref(false)

function toggleAccordion() {
  isOpen.value = !isOpen.value
}
</script>
