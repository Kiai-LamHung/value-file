<template>
  <p>{{ $route.params.group }} - {{ $route.params.id }}</p>
</template>
<script setup>
definePageMeta({
//   middleware: 'auth'
})
</script>