<template>
  <div class="home">    
    <Header> </Header>
    <Carousel></Carousel>
    <About style="padding: 1.5rem"> </About>
    <Footer class="footer"></Footer>  
  </div>
</template>   

<script>
import Header from "@/components/Header.vue";
import Carousel from "@/components/Carousel.vue";
import About from "@/components/About.vue";
import Footer from "@/components/Footer.vue";
export default {
  name: "Home",
  components: {
    Header,
    Carousel,
    About,
    Footer
  }
};
</script>
<style>
.footer {
    position:fixed;
    bottom:0;
    width:100%;
}
</style