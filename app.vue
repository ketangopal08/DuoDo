<template>
  <div>
    <NuxtPage></NuxtPage>
  </div>
</template>

<script setup lang="ts">
const colorMode = useColorMode()
colorMode.preference = 'dark'

</script>
