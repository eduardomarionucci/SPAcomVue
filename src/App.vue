<template>
  <div>
    <nav-bar logo="Social" url="#" cor="green darken-1" />

    <router-view/>
  </div>
</template>

<script>
import NavBar from '@/components/layouts/NavBar'

export default {
  name: 'app',
  components:{
    NavBar
  }
}
</script>

<style>

</style>
