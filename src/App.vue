<template>
  <div id="app">
    <Header/>
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<script>
import Router from 'vue-router'
import Header from './components/Header'
import Footer from './components/Footer'
import Login from './components/Login'
import About from './components/About'
import Contact from './components/Contact'

const routes = [
  { path: '/login', component: Login },
  { path: '/about', component: About },
  { path: '/contact', component: Contact }
]

const router = new Router({
  routes: routes,
  mode: 'history'
})

export default {
  name: 'app',
  router,
  
  components: {
   Header,
   Footer
  }
}
</script>

<style>

</style>
