<template>
  <NuxtLayout :name="layout">
    <NuxtPage />
  </NuxtLayout>
</template>

<script setup>
// You might choose this based on an API call or logged-in status
const layout = "default";
useHead({
  title: "Value File App",
  // where `%s` is replaced with the title
  titleTemplate: "%s - Site Title",
});

// state
const color = useColor(); // Same as useState('color')
</script>