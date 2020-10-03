<template>
  <v-row>
    <v-col v-for="(project, p) in projects" :key="p" cols="12" :md="4" :lg="3">
      <v-card
        min-height="300px"
        class="background lighten-1"
        style="padding: 7px"
      >
        <v-img :src="project.image" aspect-ratio="1.7" contain />

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
}
</script>
<style scoped>
.project-name {
  font-weight: bold;
  text-decoration: none;
  color: #fff !important;
}
.project-subtitle {
  font-weight: bold;
  font-size: 110%;
}
</style>
