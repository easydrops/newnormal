<template>
  <footer class="bg-salmon flex w-full justify-between align-center p-3 px-3" aria-label="Footer">
    <nuxt-link to="/" class="uppercase inline-flex items-center">New Normal 2022</nuxt-link>
    <ul class="flex">
      <li class="flex-1 p-2">
        <nuxt-link class="inline-flex items-center" to="/imprint">Imprint</nuxt-link>
      </li>
      <!--       <li class="flex-1 p-2">
        <nuxt-link class="block" to="/privacy">Privacy</nuxt-link>
      </li>
      <li class="flex-1 p-2">
        <nuxt-link class="block whitespace-nowrap" to="/terms">Terms of Use</nuxt-link>
      </li> -->
    </ul>
  </footer>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<style lang="postcss" scoped>
.nuxt-link-exact-active {
  @apply text-primary cursor-default;
}

/* Need two because of smoother switching between color modes */
@keyframes fadeIn1 {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@keyframes fadeIn2 {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
</style>
