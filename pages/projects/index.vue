<template>
  <v-row>
    <v-col v-for="(project, p) in projects" :key="p" cols="12" :md="4" :lg="3">
      <v-card
        min-height="320px"
        class="background lighten-1"
        style="padding: 7px"
        @click="$router.push(`/projects/${project.url}`)"
      >
        <v-img
          :src="project.image"
          aspect-ratio="1.7"
          contain
          class="animated fadeIn"
        />

        <v-card-title>
          <nuxt-link :to="`projects/${project.url}`" class="project-name">
            <p>{{ project.name }}</p>
          </nuxt-link>
        </v-card-title>

        <v-card-subtitle>
          <p class="project-subtitle">{{ project.discreption }}</p>
        </v-card-subtitle>
      </v-card>
    </v-col>
  </v-row>
</template>

<script>
export default {
  name: 'ProjectsIndex',
  layout: 'orion',
  computed: {
    projects() {
      return this.$store.state.projects
    },
  },
  head: {
    title: 'Projects',
    meta: [
      { property: 'og:title', hid: 'og:title', content: 'Orion Projects' },
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
<style scoped>
.project-name {
  font-weight: bold;
  text-decoration: none;
  color: #fff !important;
  font-size: 140%;
}
.project-subtitle {
  font-weight: bold;
  font-size: 120%;
}
</style>
