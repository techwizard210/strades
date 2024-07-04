<script setup>
const bannerRef = ref(null);

onMounted(() => {
  const name = useCookie('name');
  const bannerRefElem = bannerRef.value;
  if (name.value === undefined) {
    bannerRefElem.show();
  } else {
    bannerRefElem.close();
  }
});

</script>
<template>
  <div class="grow">
    <Hero />
    <CookieBanner ref="bannerRef" />
  </div>
</template>