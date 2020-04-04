<template>
  <v-layout column justify-center align-center>
    <v-flex xs12 sm8 md6>
      <div class="header-background">
        <h1>TEST</h1>
      </div>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>

<style scoped>
.header-background {
  position: relative;
  display: block;
  width: 100%;
  height: 370px;
  background: url(http://trimatrixlab.com/store/flatrica/images/backgrounds/background.jpg) no-repeat;
  background-size: cover;
  background-position: center center;
  background-attachment: fixed;
}
</style>
