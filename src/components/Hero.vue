<template>
  <div class="hero">
    <!-----desktop-->
    <div class="d-none d-md-block">
      <div class="row mt-4">
        <div class="col-md-6">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h4>
                <strong>Makan Yuk,</strong>
                <br />
                makanan enak dan bernutrisi
              </h4>
              <p>
                Ayo dilihat ,dipilih dan jangan lupa dipesan makanan favorit
                Anda
              </p>
              <button
                class="btn btn-lg btn-success bg-#F33A05"
                style="background-color: #f33a05;"
              >
                <b-icon-arrow-right></b-icon-arrow-right>
                Pesan
              </button>
            </div>
          </div>
        </div>
        <div class="col-md-6">
          <img src="../assets/images/hero.png" width="120%" />
        </div>
      </div>
    </div>

    <!----mobile-->
    <div class="d-sm-block d-md-none">
      <div class="row mt-4">
        <div class="col-md-6">
          <img src="../assets/images/hero.png" width="120%" />
        </div>
        <div class="col-md-6 mb-4">
          <div class="d-flex h-100">
            <div class="justify-content-center align-self-center">
              <h4>
                <strong>Makan Yuk,</strong>
                <br />
                makanan enak dan bernutrisi
              </h4>
              <p>
                Ayo dilihat ,dipilih dan jangan lupa dipesan makanan favorit
                Anda
              </p>
              <button
                class="btn btn-lg btn-success bg-#F33A05"
                style="background-color: #f33a05;"
              >
                <b-icon-arrow-right></b-icon-arrow-right>
                Pesan
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
  name: 'WHero',
}
</script>
<style></style>
