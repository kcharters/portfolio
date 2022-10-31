<template>
    <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">  
  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item">
        <a v-scroll-to="{ el: '#scroll-index', duration: 300 }"
      @click="$router.push({ name: 'index', hash: '#index' })" class="nav-link"  href="#">Home</a>
      </li>
      <li class="nav-item">
        <a v-scroll-to="{ el: '#scroll-about', duration: 300 }"
      @click="$router.push({ name: 'index', hash: '#about' })" class="nav-link"  href="#">About</a>
      </li>
      <li class="nav-item">
        <a v-scroll-to="{ el: '#scroll-work', duration: 300 }"
      @click="$router.push({ name: 'index', hash: '#work' })" class="nav-link"  href="#">Work</a>
      </li>
      <li class="nav-item">
        <a v-scroll-to="{ el: '#scroll-services', duration: 300 }"
      @click="$router.push({ name: 'index', hash: '#services' })" class="nav-link"  href="#">Services</a>
      </li>
      <li class="nav-item">
        <a v-scroll-to="{ el: '#scroll-contact', duration: 300 }"
      @click="$router.push({ name: 'index', hash: '#contact' })" class="nav-link"  href="#">Contact</a>
      </li>  
    </ul>    
  </div>
</nav>
</template>
<script>
export default {
    
}
</script>
<style>

</style>