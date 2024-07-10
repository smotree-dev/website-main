<script lang="ts" setup>
useHead({
  title: 'Смотри чё',
  meta: [
    {
      name: 'description',
      content: 'Видео, тексты, путешествия, приключения. Смотри чё!',
    },
  ],
})
</script>

<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<style lang="scss">
body {
  margin: 0;
}
</style>
