<template>
  <!-- some content -->
  <NuxtErrorBoundary @error="someErrorLogger">
    <!-- You use the default slot to render your content -->
    <template #error="{ error }">
      You can display the error locally here.
      <button @click="error = null">This will clear the error.</button>
    </template>
  </NuxtErrorBoundary>
</template>
<script setup>
definePageMeta({
  layout: false,
  //   middleware: 'auth'
});
throw createError({ statusCode: 404, statusMessage: "Page Not Found" });
</script>