<template>
  <div id="app">
    <router-view/>
    <FootNav/>
  </div>
</template>

<script>
import FootNav from './components/FootNav'

export default {
  name: 'App',
  components: {
    FootNav
  }
}
</script>

<style>

</style>
