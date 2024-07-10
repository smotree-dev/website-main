<template>
  <div>
    <div class="posts">
      <div class="posts__col">
        <div class="posts__col-inner">
          <ContentTelegramPost post-link="smotree_che/92" />
          <ContentTelegramPost post-link="smotree_che/93" />
          <ContentTelegramPost post-link="smotree_che/10" />
          <ContentTelegramPost post-link="smotree_che/11" />
        </div>
      </div>
      <div class="posts__col">
        <div class="posts__col-inner">
          <ContentTelegramPost post-link="smotree_che/99" />
          <ContentTelegramPost post-link="smotree_che/103" />
          <ContentTelegramPost post-link="smotree_che/88" />
        </div>
      </div>
      <div class="posts__col">
        <div class="posts__col-inner">
          <ContentTelegramPost post-link="smotree_che/87" />
          <ContentTelegramPost post-link="smotree_che/84" />
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.posts {
  display: flex;
  flex-wrap: wrap;
  gap: 32px;
  grid-auto-flow: column;

  &__col {
    flex: 1;

    &-inner {
      display: grid;
      gap: 32px;
    }
  }
}
</style>
