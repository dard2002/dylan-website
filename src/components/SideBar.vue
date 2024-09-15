<template>
  <div class="sidebar">
    <hr>
    <a href="#">About</a>
    <hr>
    <a href="#">Education</a>
    <hr>
    <a href="#">Experience</a>
    <hr>
    <a href="#">Skills</a>
    <hr>
    <a href="#">Projects</a>
    <hr>
  </div>
</template>

<script>
export default {
  name: 'SideBar',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .sidebar {
    position:fixed;
    border-left: 1px solid white;
    width:25%;
    height:100%;
    top: 0;
    right:0;
    background-color: #171717;
  }

  a {
    text-decoration: none;
  }
</style>
