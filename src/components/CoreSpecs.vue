<template>
  <div style="background-color:black;margin-top:-10px">
      <div fluid class="background" style="display:table">
          <div style="display:table-cell;vertical-align:bottom;padding-bottom:50px">
              <v-row>
                  <v-col>
                      <h1 class="white--text font-weight-light text-right">
                          1020hp
                      </h1>
                      <p class="white--text text-right">Peak Power</p>
                  </v-col>
                   <v-col>
                      <h1 class="white--text font-weight-light text-center">
                          9.9s
                      </h1>
                      <p class="white--text text-center">1/4 mile</p>
                  </v-col>
                   <v-col>
                      <h1 class="white--text font-weight-light">
                          2.5s
                      </h1>
                      <p class="white--text">0-60 mph*</p>
                  </v-col>
              </v-row>
          </div>
      </div>
  </div>
</template>

<script>

</script>

<style>
    .background {
        background: url('../../public/tesla-specs.jpeg');
        background-size:cover;
        width: 100%;
        height:70vh;
    }
</style>