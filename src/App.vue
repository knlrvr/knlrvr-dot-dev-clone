<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header className="">
    <nav className="flex items-center justify-between text-neutral-500">
      <RouterLink to="/">knlrvr</RouterLink>
      <div className="flex gap-8">
        <RouterLink to="/blog">blog</RouterLink>
        <RouterLink to="/guestbook">guestbook</RouterLink>
        <RouterLink to="/tech">tech</RouterLink>
      </div>
    </nav>
  </header>

  <RouterView />
</template>
