<template>
    <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
            <a class="navbar-brand">PROFILE</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
                <div class="navbar-nav ms-auto custom-margin">
                    <a class="nav-link me-3" aria-current="page" href="#home">Home</a>
                    <a class="nav-link me-3" href="#about">About</a>
                    <a class="nav-link me-3" href="#contact">Contact</a>
                    <a class="nav-link " href="#projects">Projects</a>
                </div>
            </div>
        </div>
    </nav>
  </template>
  
  <script>
  import HeroSection from '~/components/HeroSection.vue';
  import AboutSection from '~/components/AboutSection.vue';
  import ContactSection from './ContactSection.vue';
  import ProjectsSection from './ProjectsSection.vue';
  export default {
    name: 'NavbarSection',
    components: {
          HeroSection,
          AboutSection,
          ContactSection,
          ProjectsSection
    }
  }
  </script>
  
  <style scoped>
  .navbar {
    background-color: black;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1000;
  }
  
  .navbar-brand {
    margin-left: 150px;
    color: white;
  }
  
  .navbar-nav .nav-link {
    color: white;
    transition: color 0.3s;
  }
  
  .navbar-nav :hover {
    color: #00ff00;
  }
  
  .custom-margin {
    margin-right: 150px;
  }
  
  </style>