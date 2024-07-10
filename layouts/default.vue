<template>
  <div class="layout-default">
    <AppHeader />

    <div>
      <slot />
    </div>

    <AppFooter />
  </div>
</template>

<style lang="scss" scoped>
.layout-default {
  display: grid;
  padding: 32px;
  row-gap: 96px;
}
</style>
