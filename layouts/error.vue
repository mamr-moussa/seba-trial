<template>
  <v-row align="cener" justify="center">
    <h1 v-if="error.statusCode === 404" class="orionAmber--text">
      {{ pageNotFound }}
    </h1>
    <h1 v-else class="error--text">
      {{ otherError }}
    </h1>
    <v-col cols="12">
      <v-btn to="/" block large color="orionTeal" text
        ><b> Home page </b></v-btn
      >
    </v-col>
  </v-row>
</template>

<script>
export default {
  layout: 'orion',
  props: {
    error: {
      type: Object,
      default: null,
    },
  },
  data() {
    return {
      pageNotFound: '404 Not Found',
      otherError: 'An error occurred',
    }
  },
  head() {
    const title =
      this.error.statusCode === 404 ? this.pageNotFound : this.otherError
    return {
      title,
      meta: [
        { property: 'og:title', hid: 'og:title', content: title },
        {
          property: 'og:description',
          hid: 'og:description',
          content: 'Content Not Found',
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
    }
  },
}
</script>

<style scoped>
h1 {
  font-size: 40px;
}
</style>
