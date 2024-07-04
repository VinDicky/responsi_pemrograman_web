<template>
  <div>
    <HeroSection/>
  </div>
  <div>
    <AboutSection/>
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
import SkillSection from '~/components/NavbarSection.vue';
import ProjectsSection from '~/components/ProjectsSection.vue';
import ContactSection from '~/components/ContactSection.vue';
import NavbarSection from '../components/NavbarSection.vue';


export default {
  components: {
    HeroSection,
  }
}
</script>./Index.vue
