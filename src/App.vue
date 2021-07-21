<template>
  <div id="app">
    <Navbar/>
    <Sidebar/>
    <main>
      <Index/>
    </main>
  </div>
</template>

<style scoped>
  main {
    top: 2.9rem;
    left: 3rem;
    padding: 3.9rem 1rem 1rem 4rem;
  }
</style>

<script>
import Navbar from './components/Navbar.vue'
import Sidebar from './components/Sidebar.vue'
import Index from './pages/Index.vue'
import './assets/style.css'

export default {
  name: 'App',
  components: {
    Navbar,
    Sidebar,
    Index
  }
}
</script>
