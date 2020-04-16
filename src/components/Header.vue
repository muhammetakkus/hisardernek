<template>
  <div>
    <div class="site-mobile-menu site-navbar-target">
      <div class="site-mobile-menu-header">
        <div class="site-mobile-menu-close mt-3">
          <span class="icon-close2 js-menu-toggle"></span>
        </div>
      </div>
      <div class="site-mobile-menu-body"></div>
    </div>
    <header class="site-navbar js-sticky-header site-navbar-target" role="banner">
      <div class="container">
        <div class="row align-items-center position-relative">

          <div class="site-logo">
            <a href="index.html" class="text-black">
              <span class="text-primary" style="text-transform: capitalize !important;">Hisar</span>
            </a>
          </div>

          <nav class="site-navigation text-center ml-auto" role="navigation">
            <ul class="site-menu main-menu js-clone-nav ml-auto d-none d-lg-block">
              <li><a href="#home-section" class="nav-link">Anasayfa</a></li>
              <li><a href="#about-section" class="nav-link">Hakkımızda</a></li>
              <li><a href="#discover-section" class="nav-link">Faaliyetler</a></li>
              <li><a href="#donate-section" class="nav-link">Projeler</a></li>
              <li><a href="#blog-section" class="nav-link">Bağış</a></li>
              <li><a href="#contact-section" class="nav-link">İletişim</a></li>
            </ul>
          </nav>

          <div class="toggle-button d-inline-block d-lg-none"><a href="#" class="site-menu-toggle py-5 js-menu-toggle text-black"><span class="icon-menu h3"></span></a></div>

        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
