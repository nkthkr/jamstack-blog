<template>
  <section class="error c-flex -jc-c -ai-c">
    <h2
      class="error__title c-flex -fxd-c"
      lang="en">
      <span class="error__status">404</span>
      <span class="error__message">Page not found.</span>
    </h2>
  </section>
</template>

<style lang="scss" scoped>
.error {
  height: calc(100vh - 532px);
  color: $main-color;

  &__title {
    text-align: center;
  }

  &__status {
    font-size: 5rem;
    line-height: 1em;
  }
}
</style>
