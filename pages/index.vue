<template>
  <v-row justify="center" align="center" class="container-row">
    <v-card style="background-color: transparent; box-shadow: none">
      <v-img
        src="/imgs/orion.png"
        :height="300"
        :width="300"
        class="animated rotateIn delay"
      />
      <p class="mt-5 coc-brand-name">ORION</p>
      <p class="orion-tagline">Software Solutions</p>
    </v-card>
  </v-row>
</template>

<script>
export default {
  layout: 'orion',
  head: {
    title: 'Home',
    meta: [
      { property: 'og:title', hid: 'og:title', content: 'Orion' },
      {
        property: 'og:description',
        hid: 'og:description',
        content: 'Orion Developments for software solutions.',
      },
      {
        property: 'og:image',
        content: 'https://orionstelars.com/imgs/orion.png',
      },
      {
        hid: 'og:site_name',
        property: 'og:site_name',
        name: 'og:site_name',
        content: 'Orion Developments',
      },
    ],
  },
}
</script>
<style lang="css">
.container-row {
  height: 100vh;
}
.coc-brand-name {
  text-align: center;
  font-size: 60px;
}
.orion-tagline {
  text-align: center;
  font-size: 24px;
  margin-top: -30px;
  font-weight: bold;
}
.btn-label {
  margin-left: 4px;
  font-size: 130%;
  font-weight: bold;
  text-transform: initial;
}
.delay {
  animation-delay: 1s;
}
</style>
