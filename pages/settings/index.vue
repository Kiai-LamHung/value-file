<template>
  <div>
    <h1>I am the setting view</h1>
    <NuxtPage :foobar="123" page-key="account"/>
  </div>
</template>
<script setup>
definePageMeta({
//   middleware: 'auth'
})
</script>