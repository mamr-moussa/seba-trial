<template>
  <div v-if="project">
    <v-row justify="center" align="center">
      <v-col cols="12" md="6" lg="4">
        <v-img :src="project.image" aspect-ratio="1.7" contain />
      </v-col>
      <v-col cols="12" md="6" lg="8">
        <h1 class="project-name orionAmber--text">{{ project.name }}</h1>
        <p class="project-subtitle">{{ project.discreption }}</p>
      </v-col>
      <v-col v-if="project.pdf && isMounted" cols="12">
        <v-divider />
        <v-row align="center" justify="center">
          <v-col cols="12">
            <v-btn
              :href="project.pdf.src"
              target="_blank"
              class="z-depth-0 mb-2"
              large
              color="red"
              style="float: right"
            >
              <v-icon>mdi-adobe-acrobat</v-icon>
              <b>Download</b>
            </v-btn>
          </v-col>
          <v-col v-if="!$vuetify.breakpoint.mdAndDown" cols="1">
            <v-btn
              :disabled="currentPage <= 1"
              fab
              dark
              color="orionAmber"
              @click="goPrev"
            >
              <v-icon color="primary" size="40">mdi-chevron-left</v-icon>
            </v-btn>
          </v-col>
          <v-col cols="12" lg="10">
            <pdf
              ref="pdfViewer"
              :src="project.pdf.src"
              class="o--pdf-viewer"
              @num-pages="pageCount = $event"
              @page-loaded="currentPage = $event"
            />
          </v-col>
          <v-col v-if="!$vuetify.breakpoint.mdAndDown" cols="1">
            <v-btn
              fab
              dark
              color="orionAmber"
              :disabled="currentPage >= pageCount"
              @click="goNext"
            >
              <v-icon color="primary" size="40">mdi-chevron-right</v-icon>
            </v-btn>
          </v-col>
          <v-col cols="12">
            <v-pagination
              ref="pdfPagination"
              v-model="currentPage"
              :length="pageCount"
              circle
              @input="changePage"
            />
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </div>
</template>

<script>
import pdf from 'vue-pdf'
export default {
  name: 'ProjectSingle',
  layout: 'orion',
  components: {
    pdf,
  },
  // asyncData({ params, store }) {
  //   const filter = store.state.projects.filter((i) => i.url === params.project)
  //   const pdata = filter && filter.length ? filter[0] : null
  //   console.log('pdate', pdata)
  //   return { ...pdata }
  // },
  data() {
    return {
      pageCount: 0,
      currentPage: 0,
      isMounted: false,
    }
  },
  computed: {
    project() {
      const filter = this.$store.state.projects.filter(
        (i) => i.url === this.$route.params.project
      )
      return filter && filter.length ? filter[0] : null
    },
  },
  mounted() {
    setTimeout(() => {
      this.isMounted = true
    }, 2000)
  },
  methods: {
    changePage(e) {
      this.$refs.pdfViewer.pdf.loadPage(e)
    },
    goPrev() {
      this.changePage(this.currentPage - 1)
    },
    goNext() {
      this.changePage(this.currentPage + 1)
    },
  },
  head() {
    const project = this.project
    return {
      title: project.name,
      meta: [
        { property: 'og:title', hid: 'og:title', content: project.name },
        {
          property: 'og:description',
          hid: 'og:description',
          content: project.discreption,
        },
        {
          property: 'og:image',
          content: project.image,
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
@media only screen and (max-width: 600px) {
  .project-name {
    text-decoration: none;
    font-size: 40pt;
    font-weight: 200;
  }
  .project-subtitle {
    font-weight: bold;
    font-size: 25pt;
  }
}
@media only screen and (min-width: 601px) {
  .project-name {
    text-decoration: none;
    font-size: 80pt;
    font-weight: 200;
  }
  .project-subtitle {
    font-weight: bold;
    font-size: 25pt;
  }
}
.o--pdf-viewer {
  width: 100%;
  border-radius: 5px;
}
</style>
