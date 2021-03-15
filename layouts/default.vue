<template>
  <div>
    <Navbar />
    <SectionHeader />
    <SectionProjects />
    <!-- SectionNews -->
    <!-- SectionActors -->
    <!-- SectionWOrks -->
    <!-- Footer -->
    <!-- <Nuxt /> -->
  </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'
import SectionHeader from '@/components/pages/home/SectionHeader.vue'
import SectionProjects from '@/components/pages/home/SectionProjects.vue'

export default {
  components: {
    Navbar,
    SectionHeader,
    SectionProjects
  },
};
</script>

<style>

</style>
