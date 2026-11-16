<script setup lang="ts">
import { ref, computed, type Component } from 'vue'
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import NotFound from './views/NotFound.vue'
import NavBar from './components/NavBar.vue'
import Overview from './views/Overview.vue'
import Head from './components/Head.vue'
import ContentView from './views/ContentView.vue'
import InteractableView from './views/InteractableView.vue'
import HelpView from './views/HelpView.vue'

const routes : Record<string, Component> = {
  '/': Overview,
  '/content-hub': ContentView,
  '/interactive': InteractableView,
  '/help-center': HelpView,
  '/test': NotFound,
  // '/about': About
}

const currentPath = ref(window.location.hash)

window.addEventListener('hashchange', () => {
  currentPath.value = window.location.hash
})

const currentView = computed(() => {
  return routes[currentPath.value.slice(1) || '/'] || NotFound
})
</script>

<template>
  <header>
    <NavBar/>
    <Head/>
  </header>

  <main>
    <component :is="currentView" />
  </main>
</template>