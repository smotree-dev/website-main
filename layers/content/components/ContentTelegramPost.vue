<script lang="ts" setup>
const props = defineProps<{
  postLink: string
  userpic?: boolean
}>()

const telegramPost = computed(() => props.postLink.replace('https://t.me/', ''))
</script>

<template>
  <div :key="props.postLink" class="telegram-post">
    <ClientOnly>
      <Script
        async
        src="https://telegram.org/js/telegram-widget.js?22"
        :data-telegram-post="telegramPost"
        data-width="100%"
        data-color="254D18"
        :data-userpic="props.userpic.toString()"
      ></Script>
    </ClientOnly>
  </div>
</template>
