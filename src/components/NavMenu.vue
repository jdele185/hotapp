<template>
  <nav>
    <RouterLink to="/">Route</RouterLink>
    <RouterLink to="/other">Deliveries</RouterLink>
  </nav>
</template>

<style lang="postcss" scoped>
nav {
  @apply flex justify-center space-x-4;

  & .router-link-active {
    @apply underline underline-offset-4;
  }
}
</style>
