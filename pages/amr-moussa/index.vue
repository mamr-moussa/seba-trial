<template>
  <div>
    <v-row>
      <v-col cols="12" :md="6" :lg="4">
        <v-img
          src="/imgs/amr-moussa.jpg"
          aspect-ratio="1"
          contain
          class="personal-avatar orionAmber--text animate__animated animate__backInLeft delay"
        />
      </v-col>
      <v-col cols="12" :md="12" :lg="12">
        <p class="project-name">Amr Moussa</p>
        <p class="project-subtitle orionTeal--text">CEO and Founder</p>
      </v-col>
      <v-col cols="12" :md="12" :lg="12">
        <v-list class="background lighten-1">
          <v-list-item>
            <v-list-item-content>
              <v-list-item-title class="contact-list-text">
                Phone
              </v-list-item-title>
              <v-list-item-subtitle class="contact-list-text">
                +2 01 111 33 122
              </v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-action>
              <v-btn icon>
                <a href="tel: +201011133122" class="action-list">
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
                muhammmad.amro.moussa@gmail.com
              </v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-action>
              <v-btn icon>
                <a
                  href="mailto: +muhammmad.amro.moussa@gmail.com"
                  class="action-list"
                >
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
                <a href="/contacts/Amr_Moussa.vcf" class="action-list">
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
  transform: rotate(10deg);
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
