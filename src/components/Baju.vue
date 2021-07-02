<template>
  <div>
    <div class="row">
      <div class="col-md-4 mt-5 mb-5" v-for="(baju, index) in bajus" :key="index">
        <div class="card border-0 shadow cardBaju" style="width: 18rem">
          <img :src="baju.acuk" class="card-img-top baju" alt="loading" />
          <div class="card-body">
            <h4 class="text-center">
              <strong>{{ baju.nama }}</strong>
            </h4>
            <p class="card-text">
              <strong>Rp. {{ baju.harga }} /pcs</strong> <br />
              {{ baju.deskripsi }}
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "Baju",
  data() {
    return {
      bajus: [
        {
          nama: "Baju Kaos",
          deskripsi: "Baju yang biasa digunakan pergi jalan-jalan atau untuk bersantai",
          acuk: require("../assets/images/baju.jpg"),
          harga: "50000",
        },
        {
          nama: "Kaos Dalam",
          deskripsi: "Kaos ini cocok untuk digunakan untuk di pake dengan baju kemeja",
          acuk: require("../assets/images/baju1.jpg"),
          harga: "45000",
        },
        {
          nama: "Jas",
          deskripsi: "Jas ini dibuat dengan kain yang lembut dan cocok untuk pergi ke kantor",
          acuk: require("../assets/images/jas.jpg"),
          harga: "100000",
        },
        {
          nama: "Topi",
          deskripsi: "Topi dengan warna yang macam-macam, bisa dipakai untuk bersantai",
          acuk: require("../assets/images/topi.jpg"),
          harga: "50000",
        },
        {
          nama: "Topi",
          deskripsi: "Topi dengan warna yang macam-macam, bisa dipakai untuk bersantai",
          acuk: require("../assets/images/topi.jpg"),
          harga: "50000",
        },
        {
          nama: "Topi",
          deskripsi: "Topi dengan warna yang macam-macam, bisa dipakai untuk bersantai",
          acuk: require("../assets/images/topi.jpg"),
          harga: "50000",
        }
      ],
    };
  },
};
</script>

<style>
</style>