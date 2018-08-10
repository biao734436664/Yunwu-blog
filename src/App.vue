<template>
  <div id="app">
    <HomeLeft></HomeLeft>
    <router-view/>
  </div>
</template>

<script>
import HomeLeft from '@/components/HomeLeft'
export default {
  name: 'App',
  components: {
    HomeLeft
  }
}
</script>

<style>
</style>