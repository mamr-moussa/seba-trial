<template>
  <div>
    <v-row>
      <v-col cols="12" :md="6" :lg="4">
        <v-img :src="project.image" aspect-ratio="1.7" contain />
      </v-col>
      <v-col cols="12" :md="12" :lg="12">
        <p class="project-name">{{ project.name }}</p>
      </v-col>
      <v-col cols="12">
        <v-card-subtitle>
          <p class="project-subtitle">{{ project.discreption }}</p>
        </v-card-subtitle>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'ProjectSingle',
  layout: 'orion',
  computed: {
    project() {
      const filter = this.$store.state.projects.filter(
        (i) => i.url === this.$route.params.project
      )
      return filter && filter.length ? filter[0] : null
    },
  },
}
</script>
<style scoped>
.project-name {
  font-weight: bold;
  text-decoration: none;
  color: #fff !important;
  font-size: 200%;
}
.project-subtitle {
  font-weight: bold;
  font-size: 110%;
}
</style>
