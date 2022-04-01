<template>
<Navbar/>
<Home/>
<About/>
<Resume/>
<Projects/>
<Testimonials/>
<Contact/>
<Footer/>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import About from './components/About.vue'
import Resume from './components/Resume.vue'
import Projects from './components/Projects.vue'
import Testimonials from './components/Testimonial.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
export default {
  name: 'App',
  components: {
    Navbar,
    Home,
    About,
    Resume,
    Projects,
    Testimonials,
    Contact,
    Footer
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  /* color: #2c3e50; */
}
body {
  font-family: "Open Sans", sans-serif;
  background-color: #fff;
  color: #fff;
  position: relative;
  background: transparent;
}
body::before {
  content: "";
  position: fixed;
  background: #fff url("") top right no-repeat;
  background-size: cover;
  left: 0;
  right: 0;
  top: 0;
  height: 100vh;
  z-index: -1;
}
@media (min-width: 1024px) {
  body::before {
    background-attachment: fixed;
  }
}

a {
  color: #18d26e;
  text-decoration: none;
}

a:hover {
  color: #35e888;
  text-decoration: none;
}

h1, h2, h3, h4, h5, h6 {
  font-family: "Raleway", sans-serif;
}

</style>
