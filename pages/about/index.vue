<template>
  <v-row>
    <v-col cols="12">
      <h1 class="orionAmber--text font-weight-bold about-header">
        Who Are We?
      </h1>
      <ul class="orion-list about-content">
        <li>
          Orion is a software solutions incorporation running from 2015 all the
          way up till this moment.
        </li>
        <li>
          We cooperate with companies from all over the globe to find them
          cutting-edge solutions that fit their business.
        </li>
        <li>
          Orion contributes in the software community by many open-source
          packages available for free.
        </li>
      </ul>
    </v-col>
    <v-col cols="12">
      <h1 class="orionAmber--text font-weight-bold about-header">
        Our Concepts
      </h1>
      <ul class="orion-list about-content">
        <li>
          We believe that good solutions supply your demands, but great
          solutions evolve your industry.
        </li>
        <li>
          “The Power Of Data” is our magic word to change your industry from
          “Promising” to “Revolutionary”.
        </li>
        <li>
          We build solutions for natural human beings, you don’t have to be a
          genius to use them we promise.
        </li>
      </ul>
    </v-col>
    <v-col cols="12" class="animate__animted animate__fade delay">
      <h1 class="orionAmber--text font-weight-bold">Our Astronuts</h1>
      <v-btn text color="orionTeal" to="/amr-moussa" large class="astronut-btn">
        <v-avatar
          class="orionAmber--text avatar-cicle animate__animted animate__rotateIn delay"
          size="90"
        >
          <img src="/imgs/amr-moussa.jpg" />
        </v-avatar>
        <b class="ml-2">Amr Moussa</b>
        <b class="orionAmber--text">[CEO & Founder]</b>
      </v-btn>
    </v-col>
    <!-- <v-col cols="12" class="mt-7 animate__animted animate__fade delay">
      <v-btn
        text
        color="orionTeal"
        to="/Khaled-E-Saeed"
        large
        class="astronut-btn"
      >
        <v-avatar
          class="orionAmber--text avatar-cicle animate__animted animate__rotateIn delay"
          size="90"
        >
          <img src="/imgs/khaled-saeed.jpg" />
        </v-avatar>
        <b class="ml-2">Khaled E.Saeed</b>
        <b class="orionAmber--text">[G.Manager]</b>
      </v-btn>
    </v-col> -->
  </v-row>
</template>

<script>
export default {
  name: 'AboutIndex',
  layout: 'orion',
  data() {
    return {}
  },
  head: {
    title: 'About Us',
    meta: [
      { property: 'og:title', hid: 'og:title', content: 'About Orion' },
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
<style scope>
.orion-list {
  font-weight: bold;
  font-size: 170%;
}
.avatar-cicle {
  border-width: 2px;
  border-style: solid;
  margin-left: -20px;
}
.astronut-btn {
  height: auto !imporant;
  max-height: unset !imporant;
  margin-top: 20px;
}
.delay {
  animation-delay: 1s;
}
.about-header {
  font-size: 240%;
}
</style>
