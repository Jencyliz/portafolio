<template>
  <div>
    <Header />
    <main class="container">
      <AboutMe />
      <Projects />
      <Contact />
    </main>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import AboutMe from './components/AboutMe.vue';
import Projects from './components/Projects.vue';
import Contact from './components/Contact.vue';

export default {
  components: {
    Header,
    AboutMe,
    Projects,
    Contact
  }
}
</script>

<style>
body {
  background-color: #95a2af;
  font-family: "Roboto", sans-serif;
  font-weight: 300;
  font-style: normal;

};
</style>