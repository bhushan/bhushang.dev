<template>
  <div class="pt-6 px-4 md:px-10 lg:px-30 xl:px-40">
    <navbar />
    <Nuxt class="mb-16" />
  </div>
</template>

<script>
import Navbar from '@/components/generics/Navbar.vue';

export default {
  components: {
    Navbar,
  },
};
</script>
