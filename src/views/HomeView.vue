<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Timetable/>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Timetable from '@/views/Timetable.vue'

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    Timetable
  }
}
</script>
