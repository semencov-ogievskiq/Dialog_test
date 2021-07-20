<template>
  <div id="app">
    <Navbar/>
    <Sidebar/>
    <Main>
      <Index/>
    </Main>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Sidebar from './components/Sidebar.vue'
import Main from './components/Main.vue'
import Index from './pages/Index.vue'
import './assets/style.css'

export default {
  name: 'App',
  components: {
    Navbar,
    Sidebar,
    Main,
    Index
  }
}
</script>
