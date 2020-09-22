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
