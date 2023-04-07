<template>
  <div>
      <Promo/>
      <Specifications/>
      </Interior>
      <CoreSpecs/>
      <OrderNow/>
  </div>
</template>

<script>
  import Promo from '../components/Promo.vue'
  import Specifications from '../components/Specifications.vue'
  import Interior from '../components/Interior.vue'
  import CoreSpecs from '../components/CoreSpecs.vue'
  import OrderNow from '../components/OrderNow.vue'
export default {
  name: 'HomeView',
  components: {
    Promo,
    Specifications,
    Interior,
    CoreSpecs,
    OrderNow
  }
}
</script>
