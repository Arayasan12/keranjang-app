<template>
  <div class="pesanan-sukses">
    <MyNavbar />
    <div class="container">
      <div class="row justify-content-center mt-5">
        <div class="col-text-center">
          <img src="../assets/menunggu.png.png" width="300" />
          <h2><strong>Sukses!!</strong></h2>
          <h4>Pesanan Anda Sedang Dimasak budhe <br />Selamat Menunggu:)</h4>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MyNavbar from "@/components/MyNavbar.vue";

export default {
  name: "PesananSukses",
  components: {
    MyNavbar,
  },
};
</script>

<style>
</style>