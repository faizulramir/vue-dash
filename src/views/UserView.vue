<template>
  <div class="user">
    <h1>This is an user page</h1>
  </div>
</template>

<script>
export default {
  name: 'HomeView',
  created: function(){
    this.$emit('top-bar-title', 'User')
  }
}
</script>
