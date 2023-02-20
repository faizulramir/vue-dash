<template>
  <TopBar :topBarTitle="topBarTitle"/>
  <SideBar @top-bar-title="setTitle"/>
  <router-view @top-bar-title="setTitle"/>
</template>

<script>
import SideBar from './components/layouts/SideBar.vue'
import TopBar from './components/layouts/TopBar.vue'

export default {
  name: 'App',
  components: {
    SideBar,
    TopBar
  },
  data() {
    return {
      topBarTitle: 'Empty',
    }
  },
  methods: {
    setTitle (data) {
      this.topBarTitle = data
    }
  }
}
</script>


