<template>
    <div class="navigation-section container">
      <nav class="navbar navbar-expand-lg fixed-top">
  <div class="container-fluid">
    <img src="https://i.postimg.cc/bNZP4K6f/n-logo-removebg-preview.png" alt="Logo" width="70" height="50" class="d-inline-block align-text-top">
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <div class="">
        </div>
        <li class="nav-item">
         <RouterLink to="/">HOME</RouterLink>
        </li> 
        <li class="nav-item">
         <RouterLink to="/about">ABOUT </RouterLink>
        </li> 
        <li class="nav-item">
         <router-link to="/resume">RESUME</router-link> 
        </li>
        <li class="nav-item" >
            <RouterLink to="/projects">PORTFOLIO</RouterLink>
        </li>
        <li class="nav-item" >
            <RouterLink to="/testimonials">TESTIMONIALS</RouterLink>
        </li>
        <li class="nav-item">
          <router-link to="/contact">CONTACT</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
    </div>
</template>

<script>

export default{
}
</script>

<style  scoped>
.navbar{
 background-color:transparent;
  padding:15px;
}

.nav-item{
 padding-left: 1rem;
 
}

.navbar-toggler-icon{
  color: rgb(118, 189, 189);
}
.user-details{
  color: aqua;
}

</style>


