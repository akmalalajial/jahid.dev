<template>
  <div class="rounded-2xl overflow-hidden">
    <div class="relative h-64">
      <nuxt-img
        :src="portfolio._embedded['wp:featuredmedia']['0'].source_url"
        :alt="portfolio.title.rendered"
        class="absolute w-full h-full object-cover"
      />
    </div>
  </div>
</template>

<script>
export default {
  /* eslint-disable */
  props: ['portfolio']
  /* eslint-enable */
}
</script>

<style></style>
