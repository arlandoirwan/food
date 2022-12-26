<template>
  <div class="makan">
    <WNavbar />
    <div class="container">
      <div class="row mt-4">
        <div class="col">
          <h1>
            Daftar
            <strong>Makanan</strong>
          </h1>
        </div>
        <div class="col">
          <router-link to="/" class="btn btn-succes float-right">
            <b-icon-arrow-left></b-icon-arrow-left>
            Kembali
          </router-link>
        </div>
      </div>
      <div class="row mb-4">
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/bakso.jpg"
              class="card-img-top"
              alt="..."
              width="auto"
            />
            <div class="card-body">
              <h5 class="card-title">Bakso</h5>
              <p class="card-text">
                Harga: Rp. 10.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/sate-ayam.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Sate Ayam</h5>
              <p class="card-text">
                Harga: Rp. 20.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/mie-ayam-bakso.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Mie Ayam Bakso</h5>
              <p class="card-text">
                Harga: Rp. 16.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/nasi-rames.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Nasi Remes</h5>
              <p class="card-text">
                Harga: Rp. 10.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/kentang-goreng.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Kentang Goreng</h5>
              <p class="card-text">
                Harga: Rp. 15.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/lontong-opor-ayam.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">lontong Opor Ayam</h5>
              <p class="card-text">
                Harga: Rp. 13.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/mie-goreng.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Mie Goreng</h5>
              <p class="card-text">
                Harga: Rp. 15.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/nasi-ayam-geprek.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Nasi Ayam Gerpek</h5>
              <p class="card-text">
                Harga: Rp. 19.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/nasi-goreng-telor.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Nasi Goreng Telor</h5>
              <p class="card-text">
                Harga: Rp. 23.000
              </p>
              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
        <div class="col-md-4 mt-4">
          <div class="card shadow card-product">
            <img
              src="../assets/images/pangsit.jpg"
              class="card-img-top"
              width="auto"
              alt="..."
            />
            <div class="card-body">
              <h5 class="card-title">Pangsit</h5>
              <p class="card-text">
                Harga: Rp. 13.000
              </p>

              <b-button
                id="show-btn"
                @click="$bvModal.show('bv-modal-example')"
                size="sm"
                class="btn-succes"
              >
                <b-icon-cart></b-icon-cart>
                Pesan
              </b-button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- modal -->
    <div>
      <div>
        <b-modal id="bv-modal-example" hide-footer>
          <template #modal-title>
            <p>Konfirmasi Pesanan</p>
          </template>
          <div class="d-block text-justify">
            <label for="lname">masukan jumlah Pesanan</label>
            <br />
            <input type="number" id="lname" name="lname" />
          </div>
          <b-button
            class="mt-3"
            block
            @click="$bvModal.show('bv-modal-example2')"
            size="sm"
          >
            kirim
          </b-button>
        </b-modal>
        <b-modal id="bv-modal-example2" hide-footer>
          <template #modal-title></template>
          <div class="d-block text-justify">
            <p>pesanan di proses</p>
          </div>
          <b-button
            class="mt-3"
            block
            @click="$bvModal.hide('bv-modal-example2')"
          >
            Close Me
          </b-button>
        </b-modal>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import WNavbar from '@/components/Navbar.vue'

export default {
  name: 'WFoods',
  components: {
    WNavbar,
  },
}
</script>
