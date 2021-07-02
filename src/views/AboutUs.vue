<template>
<div id="aboutContent">
  <div class="container ">
    <div class="row">
      <div class="col-md-12 text-center text-info about mb-5">
        <h2><strong>Visi Misi</strong></h2>
      </div>
      <div class="col-md-6">
        <h3><strong>Visi</strong></h3>
        <p>Menjadi perusahaan yang terdepan dalam :</p>
        <ol>
          <li>Menjadi penyedia pakaian terpercaya di Indonesia.</li>
          <li>Menjadi perusahaan yang ramah lingkungan.</li>
          <li>
            Menjadi perusahaan konveksi yang mempunyai daya saing dan terkemuka
            di daerah dan di luar daerah.
          </li>
        </ol>
      </div>
      <div class="col-md-6">
        <h3><strong>Misi</strong></h3>
        <ol>
          <li>Menyediakan pakaian yang merupakan produk terbaik.</li>
          <li>Memberikan pelayanan terbaik pada konsumen.</li>
          <li>Menyediakan pakaian yang merupakan produk terbaik.</li>
          <li>Memberikan pelayanan terbaik pada konsumen.</li>
        </ol>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12 text-center text-info mt-5 mb-5">
        <h2><strong>Team Kami</strong></h2>
      </div>
      <div class="col-md-4">
        <div class="card border-0" style="width: 18rem">
          <img
            src="../assets/images/abdul.jpg"
            class="card-img-top team"
            alt="Owner"
          />
          <div class="card-body">
            <h4 class="card-title text-center"><strong>Abdul</strong></h4>
            <h6 class="card-title text-center text-secondary">
              <strong>( OWNER )</strong>
            </h6>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card border-0" style="width: 18rem">
          <img
            src="../assets/images/idah.jpg"
            class="card-img-top team"
            alt="Owner"
          />
          <div class="card-body">
            <h4 class="card-title text-center"><strong>Idah Rohidah</strong></h4>
            <h6 class="card-title text-center text-secondary">
              <strong>( DREKTUR UTAMA )</strong>
            </h6>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card border-0" style="width: 18rem">
          <img
            src="../assets/images/asep.jpg"
            class="card-img-top team"
            alt="Owner"
          />
          <div class="card-body">
            <h4 class="card-title text-center"><strong>Asep Dayat</strong></h4>
            <h6 class="card-title text-center text-secondary">
              <strong>( MANAGER )</strong>
            </h6>
          </div>
        </div>
      </div>
    </div>
     <div class="row mb-5">
      <div class="col-md-12 text-center mb-5 text-info">
        <h2><strong>Sejarah Perusahaan</strong></h2>
      </div>
      <div class="col-md-6">
        <p>
          BatuGajah merupakan perusahaan yang bergerak di bidang konveksi.
          Pereusahaan ini didirikan dan dikeolal oleh keluarga bapak Abdul. Saat
          ini bapak Abdul selaku penggagas berprovesi sebagai pemilik. BatuGajah
          juga menerima pesanan bersekala besar dan juga pemesanan yang
          bersekala kecil
        </p>
      </div>
      <div class="col-md-6">
        <p>
          BatuGajah berdiri pada tanggal 25 Agustus 1998. Sempat beberapa kali
          berganti nama, pada awal berdirinya BatuGajah ini bernama PT Aki Domba
          kemudian pada tahun 2000 berganti lagi menjadi PT Aki Jimu, setelah
          berjalan 3 tahun berganti lagi menjadi BatuGajah dan masih bertahan
          sampai sekarang. Nomo Surat Izin Usaha Perdagangan (SIUP):
          33/343/1998.
        </p>
      </div>
    </div>
    <div class="row">
       <div class="col-md-12 text-center mb-5 text-info">
        <h2><strong>Alamat</strong></h2>
      </div>
       <div class="col-md-6">
         <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3958.664421822253!2d108.33740381450237!3d-7.164737272288915!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6f43f18aa5b515%3A0x9500b880899c77c1!2sMadrasah%20Ibtidaiyah%20Swasta%20Babantar!5e0!3m2!1sen!2sid!4v1625239355088!5m2!1sen!2sid" width="100%" height="100%" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
       </div>
       <div class="col-md-6">
          <p>Madrasah Ibtidaiyah Swasta Babantar, Awiluar, Lumbung, Kabupaten Ciamis, Jawa Barat 46258</p>
       </div>
    </div>
  </div>
  <Footer/>
</div>
  
</template>

<script>
import Footer from '../components/Footer.vue'
export default {
  name: "About",
  components:{
    Footer
  }
};
</script>

<style>
</style>