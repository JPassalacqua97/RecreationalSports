<template>
  <div>
    <router-view name="pageContent"></router-view>
    <NavBar/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import 'vuetify/dist/vuetify.min.css'

export default {
  name: 'App',
  components: {
    NavBar
  },
}
</script>