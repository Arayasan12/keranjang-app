<template>
  <div class="hero">
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2><strong>Ada menu yang lezat,</strong> <br />Di Gedgetmu</h2>
              <p>Ayo segera pilih dan pesan makanan favorit anda</p>
              <router-link class="btn btn-lg btn-success" to="/foods">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </router-link>
            </div>
          </div>
        </div>
        <div class="col md-6">
          <img src="../assets/Hero.png.png" width="100%" />
        </div>
      </div>
    </div>
    <div class="d-sm-block d-md-none">
      <div class="row mt-4">
        <div class="col md-6 mb-3">
          <img src="../assets/Hero.png.png" width="100%" />
        </div>
        <div class="col md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h2><strong>Ada menu yang lezat,</strong> <br />Di Gedgetmu</h2>
              <p>Ayo segera pilih dan pesan makanan favorit anda</p>
              <button class="btn btn-lg btn-success">
                <b-icon-arrow-right></b-icon-arrow-right> Pesan
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MyHero",
};
</script>

<style>
</style>