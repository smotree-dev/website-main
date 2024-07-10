<template>
  <NuxtPicture class="logo" src="/images/logo.jpg" :placeholder="[25, 25]" />
</template>

<style lang="scss" scoped>
.logo {
  display: grid;

  :deep(img) {
    width: 100%;
    border-radius: 50%;
    overflow: hidden;
  }
}
</style>
