<template>
  <nav class="navbar navbar-expand-lg">
  <div class="container">
    <a class="navbar-brand" href="#">
        <img src="https://static.wixstatic.com/media/bddef3_9c3bee434dc344eb8a1f1fcd7c2db0fc~mv2.png/v1/fill/w_60,h_60,al_c,q_95,enc_auto/Circle%20Logo%20-%201.png" alt="">
    </a>
    <button class="navbar-toggler " type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item">
          <a class="nav-link" href="#" @click="$router.push({name:'home'})">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#" @click="$router.push({name:'service'})">Services</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"  @click="$router.push({name:'admission'})">Admission</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"  @click="$router.push({name:'gallery'})">Gallery</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"  @click="$router.push({name:'contact'})">Contact</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"  @click="$router.push({name:'login'})">Member Login</a>
        </li>
       
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
export default {
name:"NavbarComp"
}
</script>

<style scoped>
a{
    font-family:itali ;
    font-size: 20px;
}

</style>