
<template>
 <NavBarComp/>
  <router-view/>
  <FooterComp/>

</template>

<style>
#app {
  width: 100%;
  min-height:100vh;
  font-family:Copperplate Gothic Light;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
 
}
nav {
  padding: 80px;
  position: fixed;
  
}

 nav a {
  font-weight: bold;
  color: black;
  padding-left: 20px !important;
  text-decoration:none;
}

nav a.router-link-exact-active {
  color: rgb(250, 230, 233);
}
</style>

<script>
import NavBarComp from './components/NavBarComp.vue';
import FooterComp from './components/FooterComp.vue';


export default{
    components: {NavBarComp,FooterComp}
}
</script>