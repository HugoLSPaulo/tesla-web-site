<template>
  <div>
     <Promo/>
  <Specifications/>
  </Interior>
  <CoreSpecs/>
  </div>
</template>

<script>
  import Promo from '../components/Promo.vue'
  import Specifications from '../components/Specifications.vue'
  import Interior from '../components/Interior.vue'
  import CoreSpecs from '../components/CoreSpecs.vue'
export default {
  name: 'HomeView',
  components: {
    Promo,
    Specifications,
    Interior,
    CoreSpecs
  }
}
</script>
