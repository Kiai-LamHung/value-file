<template>
  <div>
    <NuxtLayout name="custom">
      <template #header> Some header template content. </template>
      The rest of the page
    </NuxtLayout>
  </div>
</template>
<script setup>
definePageMeta({
  layout: false,
});
</script>