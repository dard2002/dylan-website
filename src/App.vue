<template>
  <h3>{{ title }}</h3>
  <h5>{{ subtitle }}</h5>
  <SideBar />
</template>

<script>
import SideBar from './components/SideBar.vue'

export default {
  name: 'App',
  components: {
    SideBar
  },
  data() {
    return {
      title: "Dylan Armstrong",
      subtitle: "Software/Mobile Engineer and Aspiring Researcher in the field of Software Engineering"
    }
  }
}
</script>

<style>
#app {
  position: fixed;
  width: 75%;
  height: 100%;
  left:0;
  text-align: center;
  color: #ffffff;
  background-color: #20202020;
}
</style>
