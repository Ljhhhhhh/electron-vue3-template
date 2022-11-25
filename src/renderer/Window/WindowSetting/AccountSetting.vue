<script setup lang="ts">
import { onMounted } from 'vue'

onMounted(() => {
  window.opener.postMessage({ msgName: "hello", value: "I am your son." });
})
</script>
<template>
  <div>账号设置</div>
</template>
<style scoped lang="scss">

</style>
