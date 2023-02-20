<template>
  <div>
    <h1>This is an dashboard page</h1>
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  created: function(){
    this.$emit('top-bar-title', 'Dashboard')
  }
}
</script>
