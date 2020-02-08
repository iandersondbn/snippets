<template>
  <div>
    <TheNavigation />
    <nuxt />
  </div>
</template>

<script>
import TheNavigation from '@/components/global/TheNavigation.vue'

export default {
  components: {
    TheNavigation
  }
}
</script>