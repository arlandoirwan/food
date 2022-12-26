<template>
  <div id="app">
    <router-view />
    <WFooter />
  </div>
</template>
<script>
import WFooter from './components/Footer.vue'
export default {
  components: {
    WFooter,
  },
}
</script>
