<template>
  <div>
    <b-navbar toggleable="lg" type="light" class="shadow bg-white  menuNav">
      <div class="container">
        <router-link class="navbar-brand" to="/"><h2>BatuGajah</h2></router-link>

        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
             <b-navbar-nav>
            <li class="nav-item">
              <router-link class="nav-link" to="/"><h5>Home</h5></router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/produk"><h5>Produk</h5></router-link>
            </li>
            <li class="nav-item">
              <router-link class="nav-link" to="/about"><h5>About Us</h5></router-link>
            </li>
          </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </div>
    </b-navbar>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style>
</style>