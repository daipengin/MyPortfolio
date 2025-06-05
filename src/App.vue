<script setup>
import { ref, computed } from 'vue'
import Home from './components/Home.vue'
import NotFound from './components/NotFound.vue'
import Profile from './components/Profile.vue'
import Page1 from './pages/page1.vue'
import Page2 from './pages/page2.vue'


const routes = {
  '/': Home,
  '/profile':Profile,
  '/page1': Page1,
  '/page2': Page2
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
  <component :is="currentView" />
</template>