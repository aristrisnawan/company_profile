<template>
<div>
  <div class="container">
    <!-- <b-breadcrumb :items="items" class="mt-5"></b-breadcrumb> -->
    <Baju/>
  </div>
  <Footer/>
</div>
</template>

<script>
import Baju from '../components/Baju.vue'
import Footer from '../components/Footer.vue'
export default {
  name: "produk",
  components:{
    Baju,
    Footer
  },
  data() {
    return {
      items: [
        {
          text: "Admin",
          href: "#",
        },
        {
          text: "Manage",
          href: "#",
        },
        {
          text: "Library",
          href: "#",
        },
      ]
    };
  },
};
</script>

<style>
</style>