<template>
  <div>
    <Navbar />
    <Content />
    <Footer />
  </div>
</template>

<script>
import Navbar from "./components/Header";
import Content from "./components/Content";
import Footer from "./components/Footer";
export default {
  components: {
    Navbar,
    Content,
    Footer
  }
};
</script>

<style>
</style>
