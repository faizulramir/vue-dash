<template>
  <TopBar />
  <SideBar />
</template>

<script>
import SideBar from './components/layouts/SideBar.vue'
import TopBar from './components/layouts/TopBar.vue'

export default {
  name: 'App',
  components: {
    SideBar,
    TopBar
  }
}
</script>


