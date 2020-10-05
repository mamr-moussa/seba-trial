<template>
  <div>
    <v-row>
      <v-col cols="12" :md="6" :lg="4">
        <v-img
          src="/imgs/khaled-saeed.jpg"
          aspect-ratio="1"
          contain
          class="personal-avatar orionAmber--text animate__animated animate__backInLeft delay"
        />
      </v-col>
      <v-col cols="12" :md="12" :lg="12">
        <p class="project-name">Khaled E.Saeed</p>
        <p class="project-subtitle orionTeal--text">General Manager</p>
      </v-col>
      <v-col cols="12" :md="12" :lg="12">
        <v-list class="background lighten-1">
          <v-list-item v-if="showPhone">
            <v-list-item-content>
              <v-list-item-title class="contact-list-text">
                Phone
              </v-list-item-title>
              <v-list-item-subtitle class="contact-list-text">
                +20 11 49 503 962
              </v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-action>
              <v-btn icon>
                <a href="tel: +201149503962" class="action-list">
                  <v-icon color="green" class="contact-list-text">
                    mdi-phone
                  </v-icon>
                </a>
              </v-btn>
            </v-list-item-action>
          </v-list-item>
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="contact-list-text">
                E-Mail
              </v-list-item-title>
              <v-list-item-subtitle class="contact-list-text">
                khalede.saeed51@gmail.com
              </v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-action>
              <v-btn icon>
                <a href="mailto: khalede.saeed51@gmail.com" class="action-list">
                  <v-icon color="amber" class="contact-list-text">
                    mdi-email
                  </v-icon>
                </a>
              </v-btn>
            </v-list-item-action>
          </v-list-item>
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="contact-list-text">
                Add To Contacts
              </v-list-item-title>
              <v-list-item-subtitle class="contact-list-text">
                VCard
              </v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-action>
              <v-btn icon>
                <a
                  v-if="showPhone"
                  href="/contacts/khaled-saeed-full.vcf"
                  class="action-list"
                >
                  <v-icon color="blue" class="contact-list-text">
                    mdi-contacts
                  </v-icon>
                </a>
                <a
                  v-else
                  href="/contacts/khaled-saeed-secure.vcf"
                  class="action-list"
                >
                  <v-icon color="blue" class="contact-list-text">
                    mdi-contacts
                  </v-icon>
                </a>
              </v-btn>
            </v-list-item-action>
          </v-list-item>
        </v-list>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  name: 'AmrMoussa',
  layout: 'orion',
  computed: {
    showPhone() {
      return this.$route.query.t === 'j229wys7L4kkz82C'
    },
  },
  head: {
    title: 'Khaled E.Saeed',
    meta: [
      { property: 'og:title', hid: 'og:title', content: 'Khaled E.Saeed' },
      {
        property: 'og:description',
        hid: 'og:description',
        content: 'General Manager of ORION.',
      },
      {
        property: 'og:image',
        content: 'https://orionstelars.com/imgs/khaled-saeed.jpg',
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
  text-decoration: none;
  color: #fff !important;
  font-size: 40pt;
}
.project-subtitle {
  font-weight: bold;
  font-size: 20pt;
  margin-top: -15px;
}
.personal-avatar {
  border-radius: 50%;
  border-width: 3px;
  border-style: solid;
  transform: rotate(40deg);
  max-width: 200px;
}
.delay {
  animation-delay: 1s;
}
.action-list {
  text-decoration: none;
}
.contact-list-text {
  font-size: 120%;
}
</style>
