<template>
  <div id="app">
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
  name: 'App',
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
  font-family: "Roboto", serif;
  font-weight: 700;
  font-style: normal;
  margin: 0;
}

#app {
  background-image: url('@/assets/fondo2.jpg');
  background-size: cover;
  background-position: center;
  background-repeat: repeat;
  min-height: 100vh;
}
</style>
