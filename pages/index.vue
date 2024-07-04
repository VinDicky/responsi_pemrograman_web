<template>
  <div>
    <AboutSection/>
  </div>
  <div>
    <HeroSection/>
  </div>
  <div>
    <NavbarSection/>
  </div>
  <div>
    <ProjectsSection/>
  </div>
  <div>
    <ContactSection/>
  </div>
</template>

<script>
import HeroSection from '~/components/HeroSection.vue';
import AboutSection from '~/components/AboutSection.vue';

import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';



export default {
  components: {
    HeroSection,
  }
}
</script>./Index.vue
