<template>
  <v-app :style="{ backgroundColor: '#162238' }">
    <v-container style="min-height: 90vh">
      <v-row>
        <v-col cols="12" :md="12">
          <v-spacer />
          <v-btn to="/" icon x-large color="orionAmber">
            <v-avatar>
              <img
                src="/orion.ico"
                :class="[
                  'animate__animated',
                  { animate__rotateIn: onHover },
                  { animate__jello: !onHover },
                ]"
                @mouseover="onHover = true"
                @mouseleave="onHover = false"
              />
            </v-avatar>
          </v-btn>
          <v-btn
            to="/projects"
            text
            x-large
            color="orionAmber"
            style="padding: 7px"
          >
            <v-icon>mdi-atom</v-icon>
            <b class="btn-label">Projects</b>
          </v-btn>
          <v-btn
            to="/about"
            text
            x-large
            color="orionTeal"
            style="padding: 7px"
          >
            <v-icon>mdi-information-outline</v-icon>
            <b class="btn-label">About Us</b>
          </v-btn>
        </v-col>
      </v-row>
      <nuxt />
    </v-container>
    <v-footer class="justify-center background" height="70">
      <div style="width: 100%; display: block">
        <v-divider />
      </div>
      <div class="grey--text text--lighten-1 text-center">
        {{ new Date().getFullYear() }}&copy; <b>ORION</b> All Rights Reserved
      </div>
    </v-footer>
  </v-app>
</template>

<script>
export default {
  name: 'Seba',
  data() {
    return {
      onHover: false,
    }
  },

  mounted() {
    this.$vuetify.rtl = false
  },
}
</script>
<style>
*,
html,
body,
h1,
h2,
h3,
h4,
h5,
p {
  font-family: 'Josefin_Slab', sans-serif;
}
@font-face {
  font-family: 'Josefin_Slab';
  src: url('/fonts/Josefin_Slab/JosefinSlab-Regular.ttf');
  font-weight: 250;
  font-style: normal;
}
@font-face {
  font-family: 'Josefin_Slab';
  src: url('/fonts/Josefin_Slab/JosefinSlab-Bold.ttf');
  font-weight: bold;
  font-style: normal;
}
@font-face {
  font-family: 'Josefin_Slab';
  src: url('/fonts/Josefin_Slab/JosefinSlab-BoldItalic.ttf');
  font-weight: bold;
  font-style: italic;
}
@font-face {
  font-family: 'Josefin_Slab';
  src: url('/fonts/Josefin_Slab/JosefinSlab-LightItalic.ttf');
  font-weight: light;
  font-style: italic;
}
@font-face {
  font-family: 'Josefin_Slab';
  src: url('/fonts/Josefin_Slab/JosefinSlab-Light.ttf');
  font-weight: light;
  font-style: normal;
}
</style>
