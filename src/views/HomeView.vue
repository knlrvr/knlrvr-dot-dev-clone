<script setup lang="ts">
import AuthorCard from '../components/AuthorCard.vue'
import AboutSection from '../components/AboutSection.vue'
import ProjectSection from '../components/ProjectSection.vue'
import BlogSection from '../components/BlogSection.vue'
import ContactSection from '../components/ContactSection.vue'
import OnRepeat from '../components/OnRepeat.vue'
</script>

<template>
  <main class="max-w-2xl mx-auto flex flex-col space-y-16">
    <AuthorCard />
    <AboutSection />
    <ProjectSection />
    <BlogSection />
    <ContactSection />
    <OnRepeat />
  </main>
</template>
