<template>
    <div class="hero position-absolute text-dark">
  <div class="container">
      <div class="row mt-4">
        <div class="col-md-6 text-white">
          <div class="d-flex" style="height: 70vh">
            <div class="justify-content-center align-self-center">
              <h2 ><strong>BatuGajah </strong> <br />BatuGajah itu apa si ??</h2>
              <p>
                BatuGajah adalah perusahan yang bekerja<br />
                di bidang konveksi, Konveksi kami menerima berbagai macam
                pembuatan pakaian.
              </p>
              <router-link to="/foods" class="btn btn-lg btn-primary">
                <b-icon-arrow-right></b-icon-arrow-right> Order Now
              </router-link>
            </div>
          </div>
        </div>
        <div class="col-md-6 text-center text-white">
          <div class="d-flex justify-content-center" style="height:70vh;">
            <div class="justify-content-center align-self-center">
              <h2>Produk Kami :</h2>
              <h2 > <strong>
                <vue-typer
                  :text="[
                    'Baju',
                    'Celana',
                    'Jaket',
                    'Tas',
                    'Topi',
                    'Ayo Order !!!',
                  ]"
                  :pre-type-delay="70"
                  caret-animation="blink"
                  initial-action="typing"
                ></vue-typer>
              </strong></h2>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Hero",
};
</script>

<style>
</style>