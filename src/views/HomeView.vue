<template>
  <div class="home">
    <WNavbar />
    <div class="container">
      <WHero />

      <div class="row mt-5">
        <div class="col">
          <h5>
            Makanan
            <strong>Terbaik</strong>
          </h5>
        </div>
        <div class="col">
          <router-link to="/foods" class="btn btn-succes float-right">
            <b-icon-eye></b-icon-eye>
            Lihat Semua
          </router-link>
        </div>
      </div>

      <div class="row mt-3">
        <CardProduct />
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import WNavbar from '@/components/Navbar.vue'
import WHero from '@/components/Hero.vue'
import CardProduct from '@/components/CardProduct.vue'
import { RouterLink } from 'vue-router'

export default {
  name: 'HomeView',
  components: {
    WNavbar,
    WHero,
    RouterLink,
    CardProduct,
  },
}
</script>
