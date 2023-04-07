<template>
  <div>
     <Promo/>
  <Specifications/>
  </div>
</template>

<script>
  import Promo from '../components/Promo.vue'

  import Specifications from '../components/Specifications.vue'
export default {
  name: 'HomeView',
  components: {
    Promo,
    Specifications
  }
}
</script>
