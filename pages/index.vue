<template>
  <v-app>
    <v-container>
      <v-row justify="center" align="center" class="container-row">
        <v-card style="background-color: transparent; box-shadow: none">
          <v-img src="/imgs/COC-trans.png" :height="300" :width="300" />
          <p class="mt-5 pink--text coc-brand-name">COC Developments</p>
          <v-btn to="/seba"> Checkout Our New Product </v-btn>
        </v-card>
      </v-row>
    </v-container>
  </v-app>
</template>

<script>
export default {
  layout: 'seba',
  head: {
    title: 'COC Developments',
    meta: [
      { property: 'og:title', hid: 'og:title', content: 'COC, inc' },
      {
        property: 'og:description',
        hid: 'og:description',
        content: 'COC Developments for software solutions.',
      },
      {
        property: 'og:image',
        content: 'https://cocdevs.com/imgs/COC-trans.png',
      },
      {
        hid: 'og:site_name',
        property: 'og:site_name',
        name: 'og:site_name',
        content: 'COC Developments',
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
  font-family: monospace;
  font-size: 30px;
}
</style>
