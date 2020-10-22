<template>
  <div id="app">
    <menu-nav></menu-nav>
    <router-view/>
  </div>
</template>

<script>
import MenuNav from '@/components/MenuNav';

export default {
  components:{
    MenuNav,
  }

}

</script>


<style lang="scss">


body{
  background-color: $colorPrincipal;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #a8bbce;

}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #a8bbce;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
