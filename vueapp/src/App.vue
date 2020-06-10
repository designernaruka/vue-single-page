<template>
  <div id="app" class="applicaitonPage">
    <Users />
  </div>
</template>

<script>
import Users from './components/Users.vue'


export default {
  name: 'App',
  components: {
    Users
  }
}
</script>

<style lang="scss">
  @import "@/assets/scss/app.scss";
</style>